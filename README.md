# imgw-mongo-redis
Analiza danych IMGW przy użyciu baz danych Mongo DB i Redis.
Aplikacja pobiera plik archiwum ze strony IMGW, tworzy folder i rozpakowuje w nim zawartość archiwum (pliki csv).
Na podstawie plików csv, shp (pliki z geometrią województw i powiatów) oraz geojson (plik z geometrią stacji), obliczane są średnie z pomiarów dla wybranych stacji.
Projekt służył zapoznaniu się z bazami Mongo DB i Redis.
