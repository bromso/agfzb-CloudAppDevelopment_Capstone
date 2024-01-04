# Contributing

- [Submitting changes](#submitting-changes)
- [Issues and labels](#issues-and-labels)
- [Commit with Terminal commands](commit-with-terminal-commands)
- [Commit with Commitizen](#commit-with-commitizen)

## Submitting changes

If this is the first time you are contributing to an project thru gt we would really appreciate if you would read the [Open-Source.guide](https://opensource.guide/) before committing.

## Issues & labels

| Type             | Semver          | Git Label | Explanation                                                    |
| ---------------- | --------------- | --------- | -------------------------------------------------------------- |
| breaking change  | BREAKING CHANGE |           | A major change                                                 |
| bug              | fix             |           | A bug fix                                                      |
| feature          | feat            |           | A new feature                                                  |
| documentation    | docs            |           | Documentation improvements                                     |
| style            | style           |           | Changes made white-space, formatting, missing semi-colons, etc |
| refactor         | refactor        |           | A code change that neither fixes a bug nor adds a feature      |
| performance      | perf            |           | Performance improvements                                       |
| test             | test            |           | Add missing tests                                              |
| chore            | chore           |           | Changes the build process                                      |
| build            | build           |           | Change the build system or external dependencies               |
| ci               | ci              |           | Changes to our CI configuration files & scripts                |
| revert           | revert          |           | Reverts a previous commit                                      |
| released         |                 |           | Used by Semantic-Release-Bot                                   |
| duplicate        |                 |           | This issue or pull request already exists                      |
| wontfix          |                 |           | This will not be worked on                                     |
| helpwanted       |                 |           | Extra attention is needed                                      |
| question         |                 |           | Further information is requested                               |
| good first issue |                 |           | Good for newcomers                                             |

## Semantic Release

| Type                | Explanation                                                    | Semver (eg. 1.5.2) | Git Message Example                                    |
| ------------------- | -------------------------------------------------------------- | ------------------ | ------------------------------------------------------ |
| **fix**             | A bug fix                                                      | x.x.**1**          | **fix:** _update package.json_                         |
| **feat**            | A new feature                                                  | x.**1**.x          | **feat:** _add new eslint to package.json_             |
| **BREAKING CHANGE** | A major change                                                 | **1**.x.x          | **BREAKING CHANGE:** _upgrade to strapi 3 & gatsby 3_  |
| **docs**            | Documentation improvements                                     |                    | **docs:** _update README.md_                           |
| **style**           | Changes made white-space, formatting, missing semi-colons, etc |                    | **style:** _add styles in breadcrumb component_        |
| **refactor**        | A code change that neither fixes a bug nor adds a feature      |                    | **refactor:** _fixed better intendation in index.html_ |
| **perf**            | Performance improvements                                       |                    | **perf:** _add tree-shaking to webpack_                |
| **test**            | Add missing tests                                              |                    | **test:** _add test to .travis.yml_                    |
| **chore**           | Changes the build process                                      |                    | **chore:** _update .travis.yml & netlify.toml_         |

## Scopes

| Type                      | Semver | Git Label | Explanation                                                                   |
| ------------------------- | ------ | --------- | ----------------------------------------------------------------------------- |
| None                      |        |           | No scope                                                                      |
| New scope                 |        |           | Add new workspace scope (You can manage scopes in workspace `settings.json``) |
| New scope (only use once) |        |           | Use a new scope (The scope will not be added in workspace `settings.json``)   |

## Commit Type

| Type                        | Emoji | Description                                     |
| --------------------------- | ----- | ----------------------------------------------- |
| None                        | None  | No specific type (default commit)               |
| :art:                       | 🎨    | Improve structure / format of the code          |
| :zap:                       | ⚡    | Introduce performance improvements              |
| :fire:                      | 🔥    | Remove code or files                            |
| :bug:                       | 🐛    | Fix a bug                                       |
| :ambulance:                 | 🚑    | Critical hotfix                                 |
| :sparkles:                  | ✨    | Introduce new features                          |
| :memo:                      | 📝    | Add or update documentation                     |
| :rocket:                    | 🚀    | Deploy stuff                                    |
| :lipstick:                  | 💄    | Add or update the UI and style files            |
| :tada:                      | 🎉    | Celebrate a major release / big project changes |
| :white_check_mark:          | ✅    | Add or update tests                             |
| :lock:                      | 🔒    | Fix security issues                             |
| :bookmark:                  | 🔖    | Release / Version tags                          |
| :rotating_light:            | 🚨    | Fix compiler / linter warnings                  |
| :construction:              | 🚧    | Work in progress                                |
| :green_heart:               | 💚    | Fix CI build                                    |
| :arrow_down:                | ⬇️    | Downgrade dependencies                          |
| :pushpin:                   | 📌    | Pin dependencies                                |
| :construction_worker:       | 👷    | Add or update CI build system                   |
| :chart_with_upwards_trend:  | 📈    | Add or update analytics or track code           |
| :recycle:                   | ♻️    | Refactor code                                   |
| :heavy_plus_sign:           | ➕    | Add a dependency                                |
| :wrench:                    | 🔧    | Add or update configuration files               |
| :hammer:                    | 🔨    | Add or update development scripts               |
| :globe_with_meridians:      | 🌐    | Internationalization and localization           |
| :pencil2:                   | ✏️    | Fix typos                                       |
| :poop:                      | 💩    | Write bad code that needs to be improved        |
| :rewind:                    | ⏪    | Revert changes                                  |
| :twisted_rightwards_arrows: | 🔀    | Merge branches                                  |
| :package:                   | 📦    | Add or update compiled files or packages        |
| :alien:                     | 👽    | Update code due to external API changes         |
| :truck:                     | 🚚    | Move or rename resources (e.g., files, paths)   |
| :page_facing_up:            | 📄    | Add or update license                           |
| :boom:                      | 💥    | Introduce breaking changes                      |
| :bento:                     | 🍱    | Add or update assets                            |
| :wheelchair:                | ♿️   | Improve accessibility                           |
| :bulb:                      | 💡    | Add or update comments in source code           |
| :beers:                     | 🍻    | Write code drunkenly                            |
| :speech_balloon:            | 💬    | Add or update text and literals                 |
| :card_file_box:             | 🗃️    | Add or update database related changes          |
| :loud_sound:                | 🔊    | Add or update logs                              |
| :remove logs:               | 🔇    | Remove logs                                     |
| :busts_in_silhouette:       | 👥    | Add or update contributor(s)                    |
| :children_crossing:         | 🚸    | Improve user experience / usability             |
| :building_construction:     | 🏗️    | Make architectural changes                      |
| :iphone:                    | 📱    | Work on responsive design                       |
| :clown_face:                | 🤡    | Mock things                                     |
| :egg:                       | 🥚    | Add or update an easter egg                     |
| :see_no_evil:               | 🙈    | Add or update a .gitignore file                 |
| :camera_flash:              | 📸    | Add or update snapshots                         |
| :alembic:                   | ⚗️    | Experiment with new things                      |
| :mag:                       | 🔍    | Improve SEO                                     |
| :label:                     | 🏷️    | Add or update types (Flow, TypeScript)          |
| :seedling:                  | 🌱    | Add or update seed files                        |
| :triangular_flag_on_post:   | 🚩    | Add, update, or remove feature flags            |
| :goal_net:                  | 🥅    | Catch errors                                    |
| :dizzy:                     | 💫    | Add or update animations and transitions        |
| :wastebasket:               | 🗑️    | Deprecate code that needs to be cleaned up      |
| :passport_control:          | 🛂    | Work on code related to authorization           |
| :adhesive_bandage:          | 🩹    | Simple fix for a non-critical issue             |
| :monocle_face:              | 🧐    | Data exploration/inspection                     |
| :coffin:                    | ⚰️    | Remove dead code                                |
| :test_tube:                 | 🧪    | Add or update tests                             |
| :necktie:                   | 👔    | Add or update business logic                    |
| :stethoscope:               | 🩺    | Work on health metrics or health-related code   |
| :bricks:                    | 🧱    | Work on blueprints or boilerplate code          |
| :technologist:              | 🧑‍💻    | Work on developer-specific content              |
| :money_with_wings:          | 💸    | Financial or monetary updates                   |
| :thread:                    | 🧵    | Multithreading or async work                    |
| :safety_vest:               | 🦺    | Work on safety-critical code                    |

## Commit

### With Terminal commands

Our bug tracker utilizes several labels to help organize and identify issues. Here's what they represent and how we use them:

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

```sh
$ git commit -m "feat: A brief summary of the commit"
```

### With Commitizen

```sh
$ cz
```

## Git branches

| Name          | Versioning | Automated Testing | Description                                       |
| ------------- | ---------- | ----------------- | ------------------------------------------------- |
| **Main**      | Live       |                   | Production                                        |
| **[PR #1]**   |            | LHT, SRB          | Pull request made from Next to Main, BETA version |
| **Next**      | Beta       |                   | Beta/Stage, used for showcasing clients           |
| **[PR #2]**   |            | LHT, SRA          | Pull request made from Develop to Next            |
| **"Develop"** | Alpha      |                   | Alpha/Stage, used for internal tests & showcasing |
| **[PR #3]**   |            | LHT, SRA          | Pull request made from "Feature/Fix" to Develop   |
| **"Develop"** | Alpha      |                   | Alpha/Stage, used for internal tests & showcasing |

- **LHT** = Lighthouse Test
- **SRA** = Semantic Release Bot, ALPHA version
- **SRB** = Semantic Release Bot, BETA version

```text
◎ <-- Main
┃
┠══[PR #1]══╮
┃           ⊙ <-- Next (Beta)
┃           ║
┃           ║
┃           ╠──[PR #2]──╮
┃           ║           │
┃           ║           ⊙ <-- Develop (Alpha)
┃           ║           │
┃           ║           │
┃           ║           ⊙┄┄[PR #3]┄┄╮
┃           ║           │           ┆
┃           ║           │           ◌ <-- "Feature/Fix"
┃           ║           │           ┆
┃           ║           │           ┆
┃           ║           │           ┆
┃           ║           │           ┆
●           ○           ○           ◌
```

## Releases

See the Releases section of our project for [CHANGELOG](CHANGELOG.md) for each release version of Jonas Broms WWW project.

## Checking coding style

Run `npm` & `npm test` before committing to ensure your changes follow our coding standards.
