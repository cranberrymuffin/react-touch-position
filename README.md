This makes https://github.com/ethanselzer/react-touch-position compatible with React v16

To install: `npm i touch-position-react`

For further details on documentation and use please visit the origional repo: https://github.com/ethanselzer/react-touch-position

The reason for this new npm package is, right now if react-touch-position is included on an import, upon start up it throws errors because PropTypes needs a separate import + npm install of 'prop-types' as of React 15.5. Also using React.createClass was deprecated in React 16 and needs a separate require statement + npm install of 'create-react-class' to be used.
