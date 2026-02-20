# agent-test-generator-monitor

> Service: monitor for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-monitor
```

## Usage

```javascript
import { AgentTestGeneratorMonitor } from '@agent-test-generator/agent-test-generator-monitor';

const service = new AgentTestGeneratorMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
