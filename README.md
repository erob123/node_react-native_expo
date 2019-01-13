# node_react-native_expo
This README.md provides instructions/links for installing & running expo/react-native on node

<h2>Node Install</h2>
  <p>
  Node is the underlying JS server environment upon which react-native is built and run.  See <a href="https://nodejs.org/en/">node.js site</a> for more info. There are a lot of instructions on how to install node out there, but I highly recommend never using anything other than node version manager (nvm).  <code>nvm</code> does by far the best job of controlling all install files, and allows you to quickly and easily switch between versions of node, which comes in handy when dealing with packages that do not work with the newest versions of node.
  </p>
  <p>
    <ol>
      <li><a href="https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm/">Install node.js with nvm</a></li>
    </ol>
    
 <h2>Expo Install</h2>
  <p>
    Expo is a JS framework on top of react-native that allows you to quickly & easily create cross-platform mobile applications using JS.  The instructions here will install both Expo and react-native.
  </p>
  <ol>
    <li><a href="https://expo.io/learn">Expo Install Instructions</a></li>
    <li><a href="https://docs.expo.io/versions/latest/guides/up-and-running.html">Expo up and running guide</a></li>
  </ol>
    
 <h2>git install & tutorial</h2>
 <p>
  git is a version control system used for integrating/merging/reverting code, especially across teams.  All changes happen locally on your computer and then are merged to a remote repo.
 </p>
 <ol>
   <li><a href="https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-linux-md">git Install Instructions</a></li>      
   <li><a href="https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners">git Tutorial</a></li>
   <li><a href="https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes">git remote -v</li>
   <li><a href="https://github.com/cubeton/git101/blob/master/TurtorialInfo/Tutorial.md">git tutorial 2</a></li>
   <li><a href="https://education.github.com/git-cheat-sheet-education.pdf">git Cheat Sheet</a></li>
   <li><a href="https://guides.github.com/introduction/flow/">github flow</a></li>
 </ol>
 
 <h2>Nuclide/Atom IDE setup</h2>
 <p>Nuclide is an extension of the Atom IDE, designed by Facebook to work well with React and React-Native</p>
  
  <ol>
    <li><a href="https://nuclide.io/docs/editor/setup/#linux">Nuclide Setup</a></li>
    <li><a href="https://askubuntu.com/questions/1040612/how-to-install-watchman-on-ubuntu-18-04-for-react-native-error-in-make-command">Watchman Setup</a></li>
    <li><a href="https://nuclide.io/docs/platforms/react-native/#features">Nuclide React-Native (optional)</a></li>
    <li><a href="https://github.atom.io/auth/github_package/token">Link atom to github</a></li>
  </ol>
  
  <h2>React-native learning resources</h2>
    <p>
      For someone who has a programming background but no JS or react-native knowledge, reading these tutorials/articles will get you going quickly.  You can then start on a small project and continue to learn concepts as required.
    </p>    
    <ol>
  <li><a href="https://www.w3schools.com/js/default.asp">w3Schools Javascript Tutorial</a>: If you have a programming background, then you should be able to get away with reading the following sections and then referencing everything else as required for new concepts:
    <ul>
      <li>Home through Array Iteration</li>
      <li>Math</li>
      <li>Random</li>
      <li>Strict Mode</li>
      <li>ES5</li>
      <li>ES6</li>
    </ul>
  </li>
  <li>ES6 specifics:
    <ul>
      <li><a href="http://2ality.com/2014/09/es6-modules-final.html">ES6 overview</a>: Read this to get a grasp of how the ES6 syntax works/adds to legacy JS (react-native used ES6).</li>
      <li><a href="https://javascript.info/class">Classes</a>: Read for more info on JS classes</li>
      <li><a href="https://stackoverflow.com/questions/36795819/when-should-i-use-curly-braces-for-es6-import?rq=1">When should I use curly braces for ES6 imports?</a></li>
      <li><a href="https://stackoverflow.com/questions/762011/whats-the-difference-between-using-let-and-var-to-declare-a-variable-in-jav">What is the difference between <code>let</code> and <code>var</code> in javascript ES6?</a></li>
      <li><a href="https://stackoverflow.com/questions/47146106/why-does-my-javascript-getter-setter-require-underscores">Why does my javascript getter/setter require underscores?</a></li>
    </ul>
  </li>
  <li><a href="https://facebook.github.io/react-native/docs/getting-started">React-native documentation</a>: Read "the basics," then get started and reference as required!</li>
  <li>Other resources:
     <ul>
       <li><a href="https://rationalappdev.com/building-react-native-apps-on-any-platform-without-xcode-or-android-studio/">Expo description from Rational App Dev</a></li>
       <li><a href="https://rationalappdev.com/">Floating react-native tags</a></li>
       <li><a href="https://stackoverflow.com/questions/22475849/node-js-what-is-enospc-error-and-how-to-solve/32600959#32600959">Expo keeps failing due to ENOSPC error</a></li>
    </ul>
  </li>
 </ol>
