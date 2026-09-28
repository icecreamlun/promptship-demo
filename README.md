# PromptShip example prompts

A small, public prompt repository for the PromptShip regression pipeline.

The three immutable tags change only `prompts/support.md`:

- `baseline`: conservative refund intent recognition and a 30-day refund policy.
- `candidate-a`: improved intent recognition with an intentional policy regression.
- `candidate-b`: improved intent recognition while preserving policy safeguards.

The platform owns the agent runner, tools, model configuration, fixtures, and assertions. Code in this repository is never executed by the platform. All refunds are simulated. Actual evaluation results depend on model behavior and are not stored or predetermined here.
