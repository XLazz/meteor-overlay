Very EXPERIMENTAL and very simple wrapper around momentun to manage animated fullscreen overlay in Meteor

## Install

`meteor add grigio:overlay`

## Usage

Put `{{> overlay}}` inside your body tag

`Overlay.show('helloTemplate');`

or

`Overlay.show('helloTemplate',{closeable: false, title:'prova'});`

See `example/`