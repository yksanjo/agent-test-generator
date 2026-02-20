# agent-test-generator-cli

> Package 4: cli for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-cli
```

## Usage

```javascript
import { AgentTestGeneratorCli } from '@agent-test-generator/agent-test-generator-cli';

const service = new AgentTestGeneratorCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
