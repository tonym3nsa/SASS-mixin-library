# A SASS Mixin Library
A SASS Mixin library
> :grimacing: still finding time to updating this README.md

To apply a mixin to an element in your SASS file:

```
selector {
    @include mixin_name (comma separated arguments)
}
```
For example,
```
.sample-selector {
    @include two-color-vertical-gradient(#000000, #111111);
}
```

## Configuration fields
| Mixin name                    | Description                                                  | Arguements                                                                      |
| :---------------------------- | :----------------------------------------------------------- | :------------------------------------------------------------------------------ |
| two-color-vertical-gradient   | CSS vertical two-color gradient                              | $start-color: #hexcolor,</br> $end-color: #hexcolor                             |
| two-color-horizontal-gradient | CSS horizontal two-color gradient                            | $start-color: #hexcolor</br> $end-color: #hexcolor                              |
| diagonal-gradient             | CSS diagonal two-color gradient                              | $start-color: #hexcolor</br> $end-color: #hexcolor</br> $degree: decimal number |
| border-radius                 | Adding border radius to all corners of an elment             | $radius: decimal px:                                                            |
| border-top-left-radius        | Adding border radius to top left corner of an element        | $radius: decimal px:                                                            |
| border-top-right-radius       | Adding border radius to top right corner of an element       | $radius: decimal px:                                                            |
| border-bottom-left-radius     | Adding border radius to bottom left corner of an element     | $radius: decimal px:                                                            |
| border-bottom-right-radius    | Adding border radius to bottom right corner of an element    | $radius: decimal px:                                                            |
| border-bottom-radius          | Adding border radius to bottom corners of an element         | $radius: decimal px:                                                            |
| border-top-radius             | Adding border radius to top corners of an element            | $radius: decimal px:                                                            |
| border-left-side-radius       | Adding border radius to corners in the left side an element  | $radius: decimal px:                                                            |
| border-right-side-radius      | Adding border radius to corners in the right side an element | $radius: decimal px:                                                            |