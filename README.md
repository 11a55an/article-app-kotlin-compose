# Compose Article - Solution Code

This repository contains the solution code for the Compose Article practice problem. The exercise involves building a screen that displays an article about the Jetpack Compose Tutorial.

## Solution

To solve the problem, follow these steps:

1. Download the image from the URL given in the practice problem.

2. Import the image into the ComposeArticle project.

3. Use the `Column` composable function to arrange the components vertically:

```kotlin
Column(){
    // Load image using painterResource()
    Image(...)
    // Load text using stringResource()
    Text(...)
    // Load text using stringResource()
    Text(...)
}
