# audional-sequencer
A 64 step audio sample sequencer for sequencing and playing Audional base64 embedded audio JSON files

TODO - Create pixel array of the Audional logo to add to the player.
      Add a "Download, Upgrade, Inscribe" button for people to easily copy the sequencers code to their own harddrives for improving and inscribing.
      Create funtions for the "Presets" button to allow users to create sequences then save the settings. These can be hardcoded to the web player or inscribed for loading into the on-chain player.
      
      Presets look like this:
      const presets = {
    preset1: {
      urls: [
        'https://ordinals.com/content/6d962189218b836cf33e2dc1adbc981e90242aa395f0868178773065f76f144ei0',
        'https://ordinals.com/content/0b8eff3f39f4095d0f129bb8dd75f29159f8725c7e66046bf41f70ebb9f60d93i0',
        'https://ordinals.com/content/6d8be8186e63b4557e51edd66184a567bc6f5f9f5ba4bb34ba8c67e652c1934ei0'
      ],
      triggers: [
        ['1', '5', '9', '13', '17', '21', '25', '29', '33', '37', '41', '45', '49', '53', '57', '61'],
        ['1', '7', '33', '39'],
        ['62']
      ]
    },
  };
     
      Update the player to show the top tier recursive URL image from the json files to show the Audional logo for each json file.

