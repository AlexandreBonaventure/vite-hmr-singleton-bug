# vite-hmr-singleton-bug

## repro

1. `yarn && yarn dev`
2. Change this line and save: https://github.com/AlexandreBonaventure/vite-hmr-singleton-bug/blob/master/src/statefulSingleton.js#L3
3. Then change this line and save: https://github.com/AlexandreBonaventure/vite-hmr-singleton-bug/blob/master/src/useStatefulSingleton.js#L4

![before](https://github.com/AlexandreBonaventure/vite-hmr-singleton-bug/blob/master/public/before.png?raw=true)
![after](https://github.com/AlexandreBonaventure/vite-hmr-singleton-bug/blob/master/public/after.png?raw=true)
