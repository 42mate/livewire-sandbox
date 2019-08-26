# Liveriwre Sandbox

Standard Laravel install to develop Livewire

## Start the project

Run `lando start`, grab a coffee and after all is said and done you should be able to access the sanbox project on https://livewire-sandbox.lndo.site`

## Livewire local development

To do local development of the Livewire framework and see the changes instantly follow this steps once your application is up and running:

1. Go to `app/vendor/calebporzio/`
2. Move the `livewire` folder to a backup like `livewire.bak`
3. Clone the livewire repo: `git clone it@github.com:42mate/livewire.git`
4. Install npm packages: `cd livewire && npm install`
5. Launche the watch script to have your JS changes compile instantly: `npm run watch`
6. Develop away!

Once you have some code to commit and push do so from the `livewire` folder.

