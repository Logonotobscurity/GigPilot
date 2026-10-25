# Architecture — AgentBridge Africa

## Runtime topology
ContextProfile → quote worker → verifier → BudgetGuardian
Optional execute (destructive, idempotency required)

## Data contracts
ContextProfile, ToolEnvelope (read_only_hint / destructive_hint), StepResult

## Failure modes
| Failure | Behavior |
|---------|----------|
| offline_first | fail closed |
| tool_timeout / provider_error | retry budget, then fail |
| budget_exceeded | hard stop |
