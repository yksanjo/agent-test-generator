# agent-test-generator-core

> Package 1: core for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-core
```

## Usage

```javascript
import { AgentTestGeneratorCore } from '@agent-test-generator/agent-test-generator-core';

const service = new AgentTestGeneratorCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
