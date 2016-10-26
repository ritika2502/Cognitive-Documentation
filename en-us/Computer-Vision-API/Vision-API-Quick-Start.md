#Quick Start Guide

##To Generate a Caption
- Supported input methods: Raw image binary in the form of an application/octet stream or image URL.
- Supported image formats: JPEG, PNG, GIF, BMP.
- Image file size: Less than 4MB.
- Image dimension: Greater than 50 x 50 pixels.

``` 
Returned Json 
 “description”: 
{
    "captions": 
[
{
"type": "phrase",
“text”: “a black and white photo of a large city”,
          “confidence”: 0.607638706850331
}
]
"captions": 
[
{
"type": "phrase",
“text”: “a photo of a large city”,
          “confidence”: 0.577256764264197
    }
]
"captions": 
[
{
"type": "phrase",
“text”: “a black and white photo of a city”,
          “confidence”: 0.538493271791207
}
]
“description”: 
[
"tags": 
{
      "outdoor", "city", "building", "photo", "large", 
}
]
}
```

##To Analyze an Image Using Description Generator
After uploading an image or specifying an image URL, Computer Vision API’s algorithms generate a number of descriptions based on the objects identified in the image. The descriptions are each evaluated and a confidence score generated. A list is then returned ordered from highest confidence score to lowest.
- Supported input methods: Raw image binary in the form of an application/octet stream or image URL.
- Supported image formats: JPEG, PNG, GIF, BMP.
- Image file size: Less than 4MB.
- Image dimension: Greater than 50 x 50 pixels.

```
Returned Json 
 “description”: 
{
    "captions": 
[
{
"type": "phrase",
“text”: “a black and white photo of a large city”,
          “confidence”: 0.607638706850331
}
]
"captions": 
[
{
"type": "phrase",
“text”: “a photo of a large city”,
          “confidence”: 0.577256764264197
    }
]
"captions": 
[
{
"type": "phrase",
“text”: “a black and white photo of a city”,
          “confidence”: 0.538493271791207
}
]

“description”: 
[
"tags": 
{
      "outdoor", "city", "building", "photo", "large", 
}
]
}
```
