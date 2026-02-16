# [Proje Adi]

[1-2 cumle aciklama]

## Gereksinimler

- .NET 10 SDK

## Kurulum

```bash
git clone https://github.com/sunstech/[REPO_ADI].git
cd [REPO_ADI]
dotnet restore
cp .env.example .env
dotnet run
```

## Komutlar

| Komut | Aciklama |
|-------|----------|
| `dotnet run` | Development server |
| `dotnet build` | Build |
| `dotnet test` | Testleri calistir |
| `dotnet publish` | Production build |

## Tech Stack

- **Framework:** ASP.NET Core Web API
- **Dil:** C# (.NET 10)
- **API Docs:** OpenAPI (Swagger)

## Git Workflow

- `main` - Production (sadece PR ile merge)
- `develop` - Development
- `feature/xxx` - Yeni ozellik
- `fix/xxx` - Bug fix

### Commit Formati
```
feat(kapsam): yeni ozellik
fix(kapsam): hata duzeltme
docs(kapsam): dokumantasyon
refactor(kapsam): kod duzenleme
test(kapsam): test ekleme
```

## Ekip

| Rol | Kisi |
|-----|------|
| Lead | [Ad] |

## Linkler

- Trello: [Board linki]
- Slack: #proje-[ad]