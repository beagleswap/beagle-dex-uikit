# Beagle Dex UIkit

Beagle Dex UIkit is a set of React components and hooks used to build pages on Panther's apps. It also contains a theme file for dark and light mode.


## Setup

### Theme

Before using Beagle Dex UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@beagleswap-dex/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@beagleswap-dex/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
