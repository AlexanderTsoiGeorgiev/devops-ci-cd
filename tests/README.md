# 🧪 Тестове

Този проект използва **Vitest** за unit тестове.

## Структура

```
tests/
├── content.test.ts   # Тестове за валидация на съдържание
├── utils.test.ts     # Тестове за utility функции
└── build.test.ts     # Тестове за build конфигурация
```

## Команди

```bash
# Пускане на тестовете
npm test

# Пускане в watch mode
npm run test:watch

# UI за тестовете
npm run test:ui

# Code coverage
npm run test:coverage
```

## Добавяне на нови тестове

Създайте файл с `.test.ts` суфикс:

```typescript
import { describe, it, expect } from 'vitest';

describe('My Feature', () => {
  it('should work correctly', () => {
    expect(true).toBe(true);
  });
});
```

## Best Practices

1. Пишете тестове за всяка нова функционалност
2. Използвайте описателни имена за тестовете
3. Тествайте edge cases
4. Поддържайте code coverage над 80%

