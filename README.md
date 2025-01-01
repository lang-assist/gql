# Lang Assist GraphQL Schema

Lang Assist platformunun GraphQL şema ve tip tanımlamaları.

## İçerik

- `schema/`: GraphQL şema tanımlamaları
- `client/`: İstemci tarafı query ve mutation'lar

## Kullanım

Bu repository, platform genelinde kullanılan GraphQL şemalarını ve tiplerini içerir. Diğer projeler bu repository'yi bir submodule olarak kullanır.

### Server Tarafı

Server projesinde şemaları kullanmak için:

```typescript
import { typeDefs } from "@lang-assist/gql/schema";
```

### İstemci Tarafı

Mobile ve Admin Web projelerinde query'leri kullanmak için:

```typescript
import { queries } from "@lang-assist/gql/client";
```

## Geliştirme

1. Repository'yi klonlayın:

```bash
git clone https://github.com/lang-assist/gql.git
```

2. Şema değişikliklerini yapın
3. Değişiklikleri test edin
4. Pull request oluşturun

## Şema Doğrulama

```bash
npm run validate
```

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
