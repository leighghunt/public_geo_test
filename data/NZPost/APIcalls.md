JSON - locations.json: http://api.nzpost.co.nz/locator/api/locations?utf8=%E2%9C%93&api_key=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX&nearby_latitude=-41.118515&nearby_longitude=174.900498&lat1=&lng1=&lat2=&lng2=&keyword=&max=&format=json&callback=&commit=Search
CSV - nzpost_locations_20140212_1240.csv: Response type: CSV - no position returned
Google TSV - http://api.nzpost.co.nz/locator/api/locations?utf8=%E2%9C%93&api_key=be492030758a01317afe005056b855ba&nearby_latitude=-41.118515&nearby_longitude=174.900498&lat1=&lng1=&lat2=&lng2=&keyword=&max=&format=tsv&callback=&commit=Search - FAILED (too large?)
Google TSV - google_export_20140212_1402.csv - http://api.nzpost.co.nz/locator/api/locations?utf8=%E2%9C%93&api_key=be492030758a01317afe005056b855ba&nearby_latitude=&nearby_longitude=&lat1=-41.07&lng1=174.82&lat2=-41.14&lng2=174.94&keyword=&max=&format=tsv&callback=&commit=Search - worked. Remove top line, tabs -> commas, and give csv extension.

HTML - locations.html - http://api.nzpost.co.nz/locator/api/locations?utf8=%E2%9C%93&api_key=be492030758a01317afe005056b855ba&nearby_latitude=-41.118515&nearby_longitude=174.900498&lat1=&lng1=&lat2=&lng2=&keyword=&max=&format=html&callback=&commit=Search
XML - locations.xml - http://api.nzpost.co.nz/locator/api/locations?utf8=%E2%9C%93&api_key=be492030758a01317afe005056b855ba&nearby_latitude=-41.118515&nearby_longitude=174.900498&lat1=&lng1=&lat2=&lng2=&keyword=&max=&format=nzpost_xml&callback=&commit=Search

google_export_20140212_1402.geojson - from geojson.io - processed google_export_20140212_1402.csv

tsv - can't run across whole of NZ
HTML - too faffy
XML - probably best bet.