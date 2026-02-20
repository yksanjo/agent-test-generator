# agent-test-generator-sdk

> Package 3: sdk for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-sdk
```

## Usage

```javascript
import { AgentTestGeneratorSdk } from '@agent-test-generator/agent-test-generator-sdk';

const service = new AgentTestGeneratorSdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
