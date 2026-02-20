# agent-test-generator-analyzer

> Service: analyzer for AI Test Case Generator

## Installation

```bash
npm install @agent-test-generator/agent-test-generator-analyzer
```

## Usage

```javascript
import { AgentTestGeneratorAnalyzer } from '@agent-test-generator/agent-test-generator-analyzer';

const service = new AgentTestGeneratorAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
