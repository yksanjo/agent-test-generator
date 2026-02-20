# agent-test-generator-scheduler

> Service: scheduler for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-scheduler
```

## Usage

```javascript
import { AgentTestGeneratorScheduler } from '@agent-test-generator/agent-test-generator-scheduler';

const service = new AgentTestGeneratorScheduler();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
