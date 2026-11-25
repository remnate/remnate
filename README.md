# remnate

I build small tools for debugging AI developer workflows. Each project below includes a local demo and the evidence behind its results.

### Which checkout did the agent read?

[WhichTree](https://github.com/remnate/whichtree) asks a filesystem tool for the same file before and after a Git worktree switch. The returned content identifies the checkout.

### Which processes survived a reconnect?

[MCP Exit Test](https://github.com/remnate/mcp-exit-test) follows a registered MCP test server and its child through reconnect and shutdown on Linux. It writes a JUnit result for CI.

### Did a LoRA conversion change the weights that matter?

[LoRA Witness](https://github.com/remnate/lora-witness) compares supported SDXL attention updates across Kohya and Diffusers files on CPU and points to the projection where they diverge.
