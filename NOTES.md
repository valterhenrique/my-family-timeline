#NOTES

## [JSON Generator](http://www.json-generator.com/)

```js
[
  '{{repeat(5, 7)}}',
  {
    date: '{{date(new Date(0, 0, 1), new Date(), "YYYY-MM-ddThh:mm:ss Z")}}',
    isPublished: '{{bool()}}',
    events: [
      '{{repeat(3)}}',
      {
        title: '{{lorem(4, "words")}}',
		text: '{{lorem(1, "paragraphs")}}',
		picture: 'http://placehold.it/32x32',
        isPublished: '{{bool()}}',
        tags: [
          '{{repeat(7)}}',
          '{{lorem(1, "words")}}'
        ]
      }
    ]
  }
]
```
