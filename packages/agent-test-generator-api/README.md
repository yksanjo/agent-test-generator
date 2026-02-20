# agent-test-generator-api

> Package 2: api for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-api
```

## Usage

```javascript
import { AgentTestGeneratorApi } from '@agent-test-generator/agent-test-generator-api';

const service = new AgentTestGeneratorApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
