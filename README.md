# Poker Preflop Range

A Blazor WebAssembly application for poker preflop range analysis.

*Now deployed to GitHub Pages!*

## Live Demo

This application is deployed to GitHub Pages at: `https://yourusername.github.io/Poker_PreflopRange/`

## Development

### Prerequisites
- .NET 9.0 SDK

### Running Locally
```bash
dotnet run --project Poker_PreflopRange
```

### Building for Production
```bash
dotnet publish Poker_PreflopRange -c Release
```

## Deployment

This project automatically deploys to GitHub Pages when changes are pushed to the main branch using GitHub Actions.

The deployment workflow:
1. Builds the Blazor WebAssembly application
2. Publishes the release version
3. Updates the base path for GitHub Pages
4. Deploys to the `gh-pages` branch

## Technologies Used
- Blazor WebAssembly
- .NET 9.0
- Bootstrap (included in template)
