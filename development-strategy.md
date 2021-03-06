# Development Strategy

> `project-custom-video-player`

A beginner project where we work collaboratively on Document Object Model. That is a custom video player, it has play-pause button, skip buttons, changable volume-playbackrate property and clickable and interactive progressbar.

## Wireframe

![wireframe]()

## 0. Set-Up

### Repository

- Created a new repository
- Cloned the repository
- Added HTML and CSS features for user interface
- Added JS template files
- Started `development-strategy.md` file
- Created issues
- Pushed the changes
- Turned on GitHub Pages

## 1. Play-Pause Button

**As a site visitor, when i click the screen and play-pause button the video plays or pauses**

> assigned to `Oguz`  
> reviewers `Olga` , `Yauhenia` and `Sayed`

## Repo

This user story was developed on a branch called `play-pause`

## JS

- Got HTML elements with `querySelector` property
- Used `.paused` , `play()` and `pause()` methods for playing/pausing the video
- Used `eventListener` and `click` attribute

## 2. Update-toggle Button

**As a site visitor, when i click on play button it switches graphically to pause or play**

> assigned to `Yauheniya`  
> reviewers `Olga` , `Pavel` and `Oguz`

## Repo

This user story was developed on a branch called `toggle`

## JS

- Got HTML elements with `querySelector` property
- Used ternary conditional for icon switch
- Used `eventListener` and `play/pause` attribute

## 3. Volume and playback speed sliders

**As a site visitor, I can change sound level of playback while changing a volume slider and manage the playback speed with the playbackrate slider**

> assigned to `Pavel`  
> reviewers `Oguz`, `Olga` 

## Repo

This user story was developed on a branch called `volume-and-speed-sliders`

## JS

1. Initialize a collection of DOM elements with `querySelectorAll` method
2. Add a callback function for every element in collection. Callback function gets the element's `name` property and sets element's value to an appropriate player property.
3. Add `eventListener` on `change` event with the callback function, defined on step 2.


## 4. Skip-Button

**As a site visitor, when I click the forward-button, it will be forward 25 seconds, when I click back-button, it will rewind 10 seconds**

> assigned to `Olga`  
> reviewers `Oguz` , `Pavel` and `Sayed`

## Repo

This user story was developed on a branch called `skip-button`

## CSS

- add `:action` effect to skip and play buttons

## JS

- Used `.currentTime` property for sets or returns the current playback position in a video (in seconds)
- Used `.dataset.skip` property for get the time to skip
- Used `parseFloat()` function for convert time to skip to a number
- Used `eventListener` and `click` attribute for call function

## 5. Progressbar

**As a site visitor, I want to see that there is a bar showing the time update for the video so that I know how much the video finished and how much of the video time is remaining to watch**

> assigned to `Sayed`  
> reviewers `Oguz` , `Olga`

## Repo

This user story was developed on a branch called `progressbar`

## CSS

- Nothing

## JS

- the progressbar for the video
- the rangebar for the video
- event listener


## 6. Scrub Function

**As a site visitor, when I click on some part of the progressbar, it has to jump to that part of the video**

> assigned to `Sayed`  
> reviewers `Pavel` and `Yauheniya`

## Repo

This user story was developed on a branch called `scrub-function`

## CSS

Nothing

## JS

- the scrub part of the project
- even listener



