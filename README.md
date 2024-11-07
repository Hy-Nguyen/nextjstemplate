# Boiler Template for Next JS Projects

### Pre Installed Packages

- Next JS and all its goodies (NextJS, Typescript, App Router, TailwinCSS)
- Prettier
- Tailwind Prettier Plugin
- Shadcn
- React Hot Toast
- Framer Motion
- Supabase

### Predefined Tailwind Theme

- Main
  Default Color <span style="color: #88b6d3;">#88b6d3</span>

### Using this Template

1. Clone repo
   `git clone https://github.com/Hy-Nguyen/nextjstemplate.git appname `
2. Go Into Directory
   `cd ./appname`
   or
   `code ./appname`
   or
   `cursor ./appname`
3. Remove Origin
   `git remote remove origin`
4. Add New Origin
   `git remote add origin https://github.com/username/new-repo.git`
5. Push to New Repo
   `git push -u origin main`

### Creating a New Repo Using Github CLI

1. Clone repo
   `git clone https://github.com/Hy-Nguyen/nextjstemplate.git appname `
2. Go Into Directory
   `cd ./appname`
   or
   `code ./appname`
   or
   `cursor ./appname`
3. Remove Origin
   `git remote remove origin`
4. Install Github CLI
   `brew install gh`
5. Login into Github CLI
   `gh auth login`
6. Creating the New Repo
   `gh repo create <repo-name> --public`
7. Use the new link provided to add origin
   `git remove add origin https://github.com/<username>/<repo-name>.git`
8. Push to New Repo
   `git push -u origin main`

### Enviroment Variables

Supabase:

`NEXT_PUBLIC_SUPABASE_ANON_KEY=SUPABASEKEY`
`NEXT_PUBLIC_SUPABASE_URL=https://sample.supabase.co`
