## Dependency version conflict between fastmcp and pydantic

The error occurs because there's an incompatibility in how the packages are working together.

Fix: Update your dependencies

```
# OR Option 2: Fresh install
pip uninstall fastmcp pydantic pydantic-settings -y
pip install fastmcp
```

## Weather MCP Demo Fix

- `mcp_agent.py`
