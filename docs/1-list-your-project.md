# List Your Project

## 1. Fork this repository

## 2. Add your project

Modify `src/projects.json`, and add your project. Make sure it adhere to the following interface:

```typescript
interface Project {
    id: "kali",
    name: "Canto Collectives by Kali",
    description: "Legally incorporated non-profit DAOs",
    category: ["Governance", "Infrastructure", "Legal"],
    logo?: "Kali.jpg",
    website?: "https://canto.kali.gg/",
    socials?: {
        twitter?: "https://twitter.com/kali__gg",
        discord?: "discord.gg/kpMs4gzSyV"
    }
    duneQueryEmbeds?: string[]
}
```

## 3. Add your logo

Add your logo as `.jpg` or `.png` to the `src/assets/logos/` folder. Preferably 256x256px.

## 4. Open a PR

Open a PR to this repository, and we will add it as soon as the PR has been validated.
