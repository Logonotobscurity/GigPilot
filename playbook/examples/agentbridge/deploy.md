# Deploy / smoke — AgentBridge Africa

```bash
cd agentbridge
pip install -r requirements.txt
make eval
cat evals/results/latest.json
```

## Expected
success_rate_pct 100 on golden set; trajectories include failure modes.
