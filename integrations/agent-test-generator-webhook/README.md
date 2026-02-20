# agent-test-generator-webhook

> Integration: webhook for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-webhook
```

## Usage

```javascript
import { AgentTestGeneratorWebhook } from '@agent-test-generator/agent-test-generator-webhook';

const service = new AgentTestGeneratorWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
