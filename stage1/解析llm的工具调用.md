
工具调用响应示例
```python
{
  "id": "msg_01Aq9w938a90dw8q",
  "model": "claude-opus-4-7",
  "stop_reason": "tool_use",
  "role": "assistant",
  "content": [
    {
      "type": "text",
      "text": "I'll check the current weather in San Francisco for you."
    },
    {
      "type": "tool_use",
      "id": "toolu_01A09q90qw90lq917835lq9", # 此特定工具使用块的唯一标识符。这将用于稍后匹配工具结果。
      "name": "get_weather",
      "input": { "location": "San Francisco, CA", "unit": "celsius" }
    }
  ]
}
```
