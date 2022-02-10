== CONTAINER ==

  Center({
    className: string,
    id: string,
    style: object,
    child: string | element,
  })

  Column({
    className: string,
    id: string,
    style: object,
    child: string | element,
    children: array,
  })

  Row({
    className: string,
    id: string,
    style: object,
    child: string | element,
    children: array [ string | element ],
  })

  View({
    className: string,
    id: string,
    style: object,
    child: string | element,
    children: array [ string | element ],
  })
  
== CONTAINER ==

== TEXT ==

  Text({
    className: string,
    id: string,
    style: object,
    child: string | element,
    type: (tag) string,
  })

== TEXT ==

== CLICKABLE ==

  GestureDetector({
    child: string | element,
    onClick: function,
    ...(events)
  })

  Button({
    className: string,
    id: string,
    style: object,
    child: string | element,
    onPressed: function,
  })

  Link({
    className: string,
    id: string,
    style: object,
    child: string | element,
    children: array [ string | element ],
    navigate: string,
    target: string,
  })

== CLICKABLE ==

== IMAGE ==

  Image({
    className: string,
    id: string,
    style: object,
    alt: string,
    source: string,
    onPressed: function,
    sizeMode: string,
    size: array [ number | string ]
  })

== IMAGE ==

== INPUT ==

  TextInput({
    className: string,
    id: string,
    style: object,
    type: string,
    name: string,
    value: string,
    placeHolder: string,
    onBlur: function,
  })

== INPUT ==

== STYLE ==

  Style({
    selector: array [ string ] | string,
    (property): (value) string,
  })

== STYLE ==
