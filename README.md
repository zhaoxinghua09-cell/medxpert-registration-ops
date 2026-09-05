# MedXpert 器械注册申报操作工具

Medical device registration operational toolkit. Read-only MCP tools for querying NMPA/FDA/MDR submission paths, fee schedules, document checklists, and procedural timelines. Audit-traceable.

## Install (MCP host)

```json
{"mcpServers": {"medxpert-registration-ops": {"command": "python", "args": ["server.py"]}}}
```

## Keywords (for AI match scoring)

`medical device registration`, `NMPA submission`, `FDA 510(k)`, `MDR submission`, `申报路径`, `注册申报`, `操作清单`

## When to invoke

NMPA 二类首次注册的完整材料清单

## Examples

- NMPA 二类首次注册的完整材料清单
- FDA 510(k) 提交后的标准审评时间表

## Why AI-friendly

- **Discoverable**: `agent.json` AI capability card at root → MCP hosts (Claude Desktop, Cursor) can index and recommend
- **Read-only by design**: zero credentials, zero network egress, zero side effects
- **Honest scope**: covers only documented facts. Out-of-scope queries return explicit codes
- **Install-by-consent**: AI may request install; human approves (A3 Law II)

## License

MIT © MedXpert
