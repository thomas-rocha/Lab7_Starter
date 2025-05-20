1. I would keep the automated tests within a GitHub action. This would ensure that all pushes are properly tested automatically and that all pushes are tested equally.
2. No. These tests should be part of unit testing. 
3. The snapshot mode evaluates the page at its current status while the navigation mode evaluates teh page upon loading. 
4. A `lang` attribute could be added for better accessibility for international users, a `<meta name='viewport'>` tag could be added, and better fonts could be used for mobile users. 
