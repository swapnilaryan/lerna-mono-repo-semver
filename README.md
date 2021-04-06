# lerna-mono-repo-semver
This project shows how to use lerna to tagging components in GitHub using a mono-repo layout. 

This repo consists of the following components: 
- api
- mobile
- web

Each component has its own `package.json` file in charge of dealing with semver, they all are using the same approach for versioning which is based on
`semantic-release`

# Playing with versioning

If you want to check how it works from a practical perspective. Go ahead and apply a change in any component and later commit and push the changes into GitHub. 
After that, type lerna version in the terminal and then you will be prompted to answer how the version is going to be bumped:
- patch
- minor
- major

After answering the questions, you will see the tags automatically created in GitHub. Look at them here for an example of how they look like:
https://github.com/enriquezrene/lerna-mono-repo-semver/tags
