InspireCoverage.geojson - http://api.koordinates.com/api/vectorQuery.json?key=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX&layer=4022&x=174.907950179051&y=-41.11522330371197&max_results=30&radius=100000&geometry=true&with_field_names=true

4022-inspire-coverage/
4228-ufb-initiative-chorus/
4085-chorus-previously-telecom-group/
4227-ufb-initiative-enable-canterbury/
4032-telstraclear-fibre-optic-network/
4061-ufb-initiative-northpower-whangarei/
4226-ufb-initiative-ultra-fast-fibre-limited-central-north-island/
4046-telecom-wholesale-adsl2-coverage/
4227-ufb-initiative-enable-canterbury/

NO!!!
4083-rural-broadband-initiative-vodafone-wireless-final-coverage/
4084-rural-broadband-initiative-vodafone-wireless-current/


http://support.koordinates.com/hc/en-us/articles/200421184-Vector-Query

// Detailed - returns results and geometries - max 100 per layer.
http://api.koordinates.com/api/vectorQuery.json?key=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX&layer=4022&layer=4228&layer=4083&layer=4085&layer=4227&layer=4032&layer=4061&layer=4226&layer=4046&layer=4084&layer=4227&x=174.907950179051&y=-41.11522330371197&max_results=100&radius=10000&geometry=true&with_field_names=true

Takes about 2.4s, 1.5MB
Yields UFB.json
Update file to extract layers, as per contents of UFB directory.

// Quick - simply checks if there is a result - max 1 per layer
http://api.koordinates.com/api/vectorQuery.json?key=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX&layer=4022&layer=4228&layer=4083&layer=4085&layer=4227&layer=4032&layer=4061&layer=4226&layer=4046&layer=4084&layer=4227&x=174.907950179051&y=-41.11522330371197&radius=10000&with_field_names=true

Takes about 0.25s, 3KB
Yields UFB_Simple.json

