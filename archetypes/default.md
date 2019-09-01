{
  "title": "{{ $title := replace .Name "-" " " | title | lower }}{{ $title }}",
  "date": "{{ .Date }}",
  "keywords": ["podcast"],
  "episode": {
    "number": "",
    "title": "{{ $title }}",
    "subtitle": "",
    "publicationDate": "{{ .Date }}",    
    "poster": "/img/episode/{{ $title }}.png",
    "duration": "",
    "chapters": [
      {"start":"00:00:00", "title": "Intro"}
    ],
    "audio": [{
      "url": "/audio/mp4/{{ $title }}.m4a",
      "mimeType": "audio/mp4",
      "size": -1,
      "title": "Audio MP4"
    }, {
      "url": "/audio/mp3/{{ $title }}.mp3",
      "mimeType": "audio/mpeg",
      "size": -1,
      "title": "Audio MP3"
    }, {
      "url": "/audio/ogg/{{ $title }}.ogg",
      "mimeType": "audio/ogg",
      "size": -1,
      "title": "Audio Ogg"
    }, {
      "url": "/audio/opus/{{ $title }}.opus",
      "mimeType": "audio/opus",
      "size": -1,
      "title": "Audio Opus"
    }],
    "contributors": [{
      "id": "emil-example",
      "avatar": "/img/avatar/blank_50.png",
      "name": "Emil Example"
    }],
    "tabs": ""
  },
  "draft": false
}

Gib hier die Zusammenfassung der Folge ein. 

<!--more--> 

Für hier die Show Notes ein.