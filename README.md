Steps to do:

yarn init -y && yarn add -D @storybook/react babel-core && yarn add react react-dom

mkdir .storybook src
touch .storybook/config.js

"scripts": { "storybook": "start-storybook -p 6006 -c .storybook" }
