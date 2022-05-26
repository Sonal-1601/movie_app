# movie_preview

A flutter project to show movie details with flutter API integration
Used Get Method



## Working![movie_poster](https://user-images.githubusercontent.com/71246954/170436411-9e2aeaa1-d070-46ae-959e-58da628a84e3.jpeg)
![movie_poster (2)](https://user-images.githubusercontent.com/71246954/170436415-79a79514-b214-4068-aa54-e61b5430590c.jpeg)
![movie_poster (3)](https://user-images.githubusercontent.com/71246954/170436418-9b067a10-ce14-4e72-b7a5-0044cb8c882a.jpeg)
![movie_poster (4)](https://user-images.githubusercontent.com/71246954/170436420-4207184a-c12a-4d1d-84c2-ba06f884346d.jpeg)
![movie_poster (5)](https://user-images.githubusercontent.com/71246954/170436422-cdceaf5a-2325-4062-8c45-f31505fbe68a.jpeg)


MaterialApp uses routes generated from [generateRoute method](https://github.com/Sonal-1601/movie_preview/blob/15ce35b88c96eb45ea6835ed00305246b7b3b3c1/lib/commons/routes.dart#L23) and themes from [themeData in lib/commons/styles.dart](https://github.com/Sonal-1601/movie_preview/blob/15ce35b88c96eb45ea6835ed00305246b7b3b3c1/lib/commons/styles.dart#L3)

[Media](https://github.com/Sonal-1601/movie_preview/blob/15ce35b88c96eb45ea6835ed00305246b7b3b3c1/lib/models/plain/media.dart#L10) is the plain model class for json data recieved from the API. The raw json response is parsed by the [MediaRepository](https://github.com//movie_preview/blob/master/lib/models/repository/media.dart) which stores list of [Media](https://github.com/Sonal-1601/movie_preview/blob/15ce35b88c96eb45ea6835ed00305246b7b3b3c1/lib/models/plain/media.dart#L10)

Application uses stream controller from [MediaRepository](https://github.com/Sonal-1601/movie_preview/blob/master/lib/models/repository/media.dart) to update & make api calls using the [MediaAPIClient](https://github.com/Sonal-1601/movie_preview/blob/master/lib/api/client.dart).
