# ZeytoonArtFrame

- Zeytoon Art Frame is a JavaScript Library .
- Quick and easy frame art making .
- Suitable for image galleries and artwork .

Create a wooden frame with flowers in the corners and in the middle.
![](https://raw.githubusercontent.com/rostamkhani/ZeytoonArtFrame/master/SampleReadme1.jpg "wooden frame")

Wooden frame with only corners.
![](https://raw.githubusercontent.com/rostamkhani/ZeytoonArtFrame/master/SampleReadme2.jpg)

------------

####Sample Usage:
```javascript
        var zeytoonAF = new ZeytoonArtFrame(
            get('MyContent1'),                   // Html Element Content 
            'Image/Artwork/pic(1).jpg',      // Image
            {                                                // Options
                WidthImage: 'auto',
                HeightImage: '550px',
                FrameWidth: '35px',
                FrameStyleNumber: 11,
                FrameCorner: true,
                FrameCenter: true
            }
        );

```
#### ZeytoonArtFrame Parameters
|#| Name | Description                    | Sample Value                            |Default Value|
|-| ----------- | ----------------------------------- |----------------------------|------|
|1| content      | Element content to display the art frame        |  doucument.getElementById ('MyContent1')|No|
|2| Image URL   |  Image address   | 'Image/Artwork/pic(1).jpg' | No|
|3| Options | Frame options JSON |  See table options| Yes |

###Frame Options:
|#| Name | Sample Value                            |Default Value|
|-| ----------- | ----------------------------|------|
|1| WidthImage | '600px' or 'auto' | 'auto' |
|2| HeightImage | '600px' or 'auto'  | '500px' |
|3| FrameWidth | '120px' or 'auto' | 'auto' |
|4| FrameStyleNumber | 8 | 1 |
|5| FrameCorner | true or false | false |
|6| FrameCenter | true or false | false |
```json
var DefaultOptions = {
        WidthImage: 'auto',
        HeightImage: '500px',
        FrameWidth: 'auto',
        FrameStyleNumber: 1,
        FrameCorner: false,
        FrameCenter: false
    } ;
```

