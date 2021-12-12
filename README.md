# Directus themes

CSS Themes for the directus interface

## Installation

Just go to `Settings > Project Settings`
and copy the CSS into the `Custom CSS` part

## Themes

### Grey

![Alt text](/images/grey-light.jpg?raw=true "Optional Title")
![Alt text](/images/grey-dark.jpg?raw=true "Optional Title")

```css
/* Grey Theme */
/* Global */
#app,
#main-content {
  --border-radius-outline: 16px !important;
  --border-radius: 16px !important;
}

.v-list-item {
  --v-list-item-border-radius: 16px !important;
}

/* Dark */
body.dark {
  color-scheme: dark;
  --border-normal: #3b3b3b !important;
  --border-normal-alt: #707070 !important;
  --border-subdued: #272727 !important;
  --foreground-normal: #b0b0b0 !important;
  --foreground-normal-alt: #cecece !important;
  --foreground-subdued: #636363 !important;
  --foreground-inverted: #202020 !important;
  --background-normal: #262626 !important;
  --background-normal-alt: #3f3f3f !important;
  --background-subdued: #282828 !important;
  --background-highlight: #282828 !important;
  --background-page: #202020 !important;
  --background-input: #202020 !important;
  --background-page-rgb: 28, 28, 28 !important;
  --background-inverted: #fff !important;
  --card-face-color: #303030 !important;
  --card-shadow-color: 0, 0, 0 !important;
  --overlay-color: rgba(19, 19, 19, 0.9) !important;
  --module-background: #101010 !important;
  --module-icon: #7d7d7d !important;
}

@media (prefers-color-scheme: dark) {
  body.auto {
    color-scheme: dark;
    --border-normal: #3b3b3b !important;
    --border-normal-alt: #707070 !important;
    --border-subdued: #272727 !important;
    --foreground-normal: #b0b0b0 !important;
    --foreground-normal-alt: #cecece !important;
    --foreground-subdued: #636363 !important;
    --foreground-inverted: #202020 !important;
    --background-normal: #262626 !important;
    --background-normal-alt: #3f3f3f !important;
    --background-subdued: #282828 !important;
    --background-highlight: #282828 !important;
    --background-page: #202020 !important;
    --background-input: #202020 !important;
    --background-page-rgb: 28, 28, 28 !important;
    --background-inverted: #fff !important;
    --card-face-color: #303030 !important;
    --card-shadow-color: 0, 0, 0 !important;
    --overlay-color: rgba(19, 19, 19, 0.9) !important;
    --module-background: #101010 !important;
    --module-icon: #7d7d7d !important;
  }
}

/* Light */
body.light {
  --border-normal: #ececec !important;
  --border-normal-alt: #202020 !important;
  --border-subdued: #f5f5f5 !important;
  --foreground-normal: #5b5b5b !important;
  --foreground-normal-alt: #444 !important;
  --foreground-subdued: #aaa !important;
  --foreground-inverted: #fff !important;
  --background-normal: #f7f7f7 !important;
  --background-normal-alt: #e9e9e9 !important;
  --background-subdued: #fafafa !important;
  --background-highlight: #fafafa !important;
  --background-page: #ffffff !important;
  --background-input: #ffffff !important;
  --background-page-rgb: 255, 255, 255 !important;
  --background-inverted: #262626 !important;
  --card-face-color: #fafafa !important;
  --card-shadow-color: 23, 23, 23 !important;
  --overlay-color: rgba(50, 50, 50, 0.9) !important;
  --module-background: #202020 !important;
  --module-icon: #8d8d8d !important;
}

@media (prefers-color-scheme: light) {
  body.auto {
    --border-normal: #ececec !important;
    --border-normal-alt: #202020 !important;
    --border-subdued: #f5f5f5 !important;
    --foreground-normal: #5b5b5b !important;
    --foreground-normal-alt: #444 !important;
    --foreground-subdued: #aaa !important;
    --foreground-inverted: #fff !important;
    --background-normal: #f7f7f7 !important;
    --background-normal-alt: #e9e9e9 !important;
    --background-subdued: #fafafa !important;
    --background-highlight: #fafafa !important;
    --background-page: #ffffff !important;
    --background-input: #ffffff !important;
    --background-page-rgb: 255, 255, 255 !important;
    --background-inverted: #262626 !important;
    --card-face-color: #fafafa !important;
    --card-shadow-color: 23, 23, 23 !important;
    --overlay-color: rgba(50, 50, 50, 0.9) !important;
    --module-background: #202020 !important;
    --module-icon: #8d8d8d !important;
  }
}
```
