
# Design Patterns in TypeScript

This repository contains implementations of the 23 Gang of Four (GoF) design patterns using TypeScript.

## Patterns Included

### Creational Patterns
- Abstract Factory
- Builder
- Factory Method
- Prototype
- Singleton

### Structural Patterns
- Adapter
- Bridge
- Composite
- Decorator
- Facade
- Flyweight
- Proxy

### Behavioral Patterns
- Chain of Responsibility
- Command
- Interpreter
- Iterator
- Mediator
- Memento
- Observer
- State
- Strategy
- Template Method
- Visitor

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the examples:
   ```bash
   npm start
   ```

## Project Structure
Each pattern is implemented in its own directory under the appropriate category (creational/structural/behavioral).
Each pattern implementation includes:
- Main implementation files
- Example usage
- README explaining the pattern

## Building
```bash
npm run build
```
```

6. Create the directory structure with this bash script:

```bash
# Create main directories
mkdir -p src/{creational,structural,behavioral}

# Create pattern directories
# Creational
mkdir -p src/creational/{abstract-factory,builder,factory-method,prototype,singleton}

# Structural
mkdir -p src/structural/{adapter,bridge,composite,decorator,facade,flyweight,proxy}

# Behavioral
mkdir -p src/behavioral/{chain-of-responsibility,command,interpreter,iterator,mediator,memento,observer,state,strategy,template-method,visitor}

# Create tests directory
mkdir tests

# Create empty index.ts
touch src/index.ts
```

To start implementing the patterns, you can now:
1. `cd design-patterns-typescript`
2. Run the setup commands
3. Run the directory creation script
4. Start implementing each pattern in its respective directory

Each pattern's directory should typically contain:
- An implementation file (e.g., `abstract-factory.ts`)
- An example file (e.g., `abstract-factory-example.ts`)
- A pattern-specific README.md explaining the pattern's purpose and usage
