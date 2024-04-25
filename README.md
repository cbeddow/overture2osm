# overture2osm
Tools for converting Overture Maps Foundation data to OpenStreetMap tags and formats

Notes: 

1. structure_and_geography category from Overture has been ignored -- too vague and broad to match to a single set of tags
2. some Overture categories have typos, I reported these to Overture -- the pretty name for them has correct spelling
3. I will look to add some of my cleaned up Python scripts for looking at the data
4. I plan to do a search of all the OSM iD icons to see if I misspelled or am missing any
5. some of the OSM tags are newly invented but try to adhere to OSM spirit - open for debate
6. skyline as a category is also removed -- this is an error

Exploring the Overture data is rather easy if you locally download the data then open in Python and compare to this dict. Recommended guide: https://til.simonwillison.net/overture-maps/overture-maps-parquet

