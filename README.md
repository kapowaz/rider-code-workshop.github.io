# Rider Workshop exercise

## Creating your website

1. Visit github.com and create an account. Your username will form part of your website address, so choose it carefully — for example, if you choose `khaleesi2017` as your username, your website will be at `khaleesi2017.github.io`. Sign up using an email address you have access to right now.
2. You’ll be asked to verify your email address, so log into your email and follow the link in the email you receive from GitHub.
3. Launch _GitHub Desktop_ from the Dock or Task bar, and log in using your new user account.
4. Once you’re logged in, click the “Create New Repository” button on the left side of the window. You will be prompted to enter:
    1. The repository name. This should be your username that you used to sign up with, followed by `.github.io` — e.g. `khaleesi2017.github.io`
    2. The local path. This is the location on your computer where your source code will be placed — choose a location you’re happy with
5. Click Create Repository to confirm these settings
6. From the Repository menu, choose Open in Finder to open up your new project folder in the Finder (on Mac) or in File Explorer (on Windows)
7. Drag this folder (it should be called something like `khaleesi2017.github.io`) from the Finder or File Explorer to the _Sublime Text_ icon on your Dock or Task Bar to open it in the _Sublime Text_ editor
8. In the _Sublime Text_ editor window, right-click the folder on the left hand side, and choose New File, then press Command-S (or File > Save) to save it, and call it `index.html`
9. Time to get started with the exercise!

## Making your profile page

All the requirements can be met with plain HTML without any CSS. Yes it will be an ugly page - that’s ok.

Students creating their profile page should try to have one of each of these things in their page:

1. A main heading on the page with your name in it
2. A photo of yourself
3. A medium-length ‘about me’ description of yourself; talk about the kind of vehicle you use to deliver etc.
4. A list of things related to you, such as:
    1. Your favourite foods (maybe in order of preference?)
    2. Zones you’ve delivered in
    3. Links to your social media presence, Facebook page, Twitter profile etc.
    4. Your hobbies
    5. A link to your favourite sports team’s website
    6. Any other interesting list of things you can think of
5. (optional) embed a widget, e.g. your Strava profile, Soundcloud player, Spotify playlist, Twitter timeline, a favourite YouTube video etc.

## Making your profile page _look nicer!_

First of all, use the Web Inspector tools to change and play with your layout dynamically. Some ideas for things students might want to try playing with to improve how their profile page looks:

1. Change the typography
2. Change the background and text colour
3. Give the layout a maximum width so that it doesn’t occupy the whole width of the window at larger sizes
4. Make your “about me” text sit alongside your photo (`float` plus `clear` — more advanced!)
5. GO NUTS!

## Publishing your website

Once you’ve completed your website and are ready to publish it, you can do this with GitHub Desktop, so switch back to it.

1. On the left hand side of the window you should see a list of all the files you’ve created as part of your exercise, including one called index.html. If you called your page something else, you’ll want to go back and change it to this right now, otherwise your website won’t work!
2. Everything you’ve created and want to be published needs to have a checkmark beside it.
3. At the bottom left you will see a couple of text boxes. In ‘Summary’, write a short message — it’s not important what, something like “My first commit!” works fine
4. Click the button that says “Commit to master”

**Each tutor should have a go at the exercise and share a screenshot in advance!**

## Concepts to learn about

1. Semantic markup: headings, images, paragraphs, links, lists
2. `<style>` tag vs `<link rel="stylesheet">`
3. `font-family`
4. `color` and `background-color`, and how colour codes work (hex, rgb)
5. container elements, `width` and `margin`
6. `display: float;`

Extra properties/stuff that would be cool to learn about (possibly ad hoc as part of the exercise):

1. Media queries
2. `:hover`
3. `text-shadow`, `border`, `border-radius`, `box-shadow`, `text-transform`
4. transitions, transforms, animations, opacity

## Tutor further reading/explanation materials

1. Colour reference (also RGB/hex values)
2. Layout stuff (`position: absolute` vs `position: relative`, box model)
