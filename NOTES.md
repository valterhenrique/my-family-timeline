#NOTES

## [JSON Generator](http://www.json-generator.com/)

```js
[
  '{{repeat(5, 7)}}',
  {
    title: '{{lorem(3, "words")}}',
    description: '{{lorem(5, "words")}}',
    isActive: '{{bool()}}',
    events: [
      '{{repeat(3)}}',
      {
        title: '{{lorem(4, "words")}}',
		text: '{{lorem(1, "paragraphs")}}',
        date: '{{date(new Date(1900, 0, 1), new Date(), "YYYY-MM-ddThh:mm:ss Z")}}',
		picture: 'http://placehold.it/32x32'
      }
    ],
    tags: [
      '{{repeat(7)}}',
      '{{lorem(1, "words")}}'
    ]
  }
]
```
