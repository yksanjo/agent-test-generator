# agent-test-generator-connectors

> Package 5: connectors for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-connectors
```

## Usage

```javascript
import { AgentTestGeneratorConnectors } from '@agent-test-generator/agent-test-generator-connectors';

const service = new AgentTestGeneratorConnectors();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
