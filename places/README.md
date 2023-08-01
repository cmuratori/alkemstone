# Places (possibly) connected to Alkemstone

These files contain coordinates of places that seem to be referenced by clues in Alkemstone. The CSV and GeoJSON files with the same names contain essentially the same data in different forms. You should be able to plot the locations on a map by viewing either file type at [GeoJSON.io](http://geojson.io/). The CSV should be easier to read and edit, but GeoJSON gives you the added ability to draw lines and shapes on the map.

It might not be obvious why all the locations are considered potential riddle solutions, but background discussion can be found on the [Renga in Blue blog](https://bluerenga.blog/tag/alkemstone/?order=ASC) (including the linked spreadsheet of images and theories).

At the moment, all the mapped locations are in Washington, DC.

## Column Definitions

- lat, long: The coordinates of the landmark, used for plotting points on the map.
- landmark: Name of the landmark that seems to be referenced by an Alkemstone riddle.
- location_description: Human-readable description of where the landmark is.
- hint_number: The number of the message in Alkemstone that seems to reference this location. These numbers correspond to filenames in the `orig_clues` folder of this repo. If past puzzlers felt indecisive, there may be multiple possible numbers.
- hint_text: The text of the in-game message(s) suggesting this location, or a description of the hint if it's not a text message.
- game_grid_x: a decimal number from 1 to 32 (not hexadecimal), indicating the x coordinate of the hint on the grid shown in `fullalkmap.png` in this repo. The leftmost column will be number 1, not 0.
- game_grid_y: a decimal number from 1 to 17 indicating the y coordinate of the hint in `fullalkmap.png`. The top row will be number 1.