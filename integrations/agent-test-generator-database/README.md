# agent-test-generator-database

> Integration: database for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-database
```

## Usage

```javascript
import { AgentTestGeneratorDatabase } from '@agent-test-generator/agent-test-generator-database';

const service = new AgentTestGeneratorDatabase();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
