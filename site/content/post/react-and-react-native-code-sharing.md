---
title: 'React and React native code sharing '
date: 2030-01-30T15:21:13.542Z
description: >-
  90% of your react app and react native app has similar code for example if you
  are using some sort of state management system like redux, there probably you
  can share actions,  reducers and etc. In my case, there are only the UI
  components which differ from each other. So let's find out about the way we
  can share out code between the React and ReactNative.
---
If you do a google search you will be able to find many approaches. But most of them are talking about "write once and runs everywhere", but in my case I needed to separate the react (web components) and the react native (mobile components).
