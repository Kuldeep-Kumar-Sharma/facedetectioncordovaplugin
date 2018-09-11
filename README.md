# facedetectioncordovaplugin
cordova plugin for face detection using google vision API,that can be used in ionic  or any other cordova based applications.

## Tested With

| Version's        | should be above |
| ------------- |:-------------:|
| java     | >=1.7 |
| Cordova      | >=7.0.0      |

To use facedetection Cordova Plugin Simply Use the Following code to your once you have installed in your project.

```typescript
 window['plugins'].start.camera(
      "", (result) => {
        //include --> import { DomSanitizer } from '@angular/platform-browser';
        // and --> public sanitizer: DomSanitizer
        let image = this.sanitizer.bypassSecurityTrustUrl("data:image/*;base64,"+result);
        this.image = image;
      },
      (err) => {
        console.log(err);
      },
    );
```

## Running and Testing

Please install by the following command

```
cordova plugin add --link https://github.com/Kuldeep-Kumar/facedetectioncordovaplugin.git
```


## Built With

*  [Cordova Plugman](https://cordova.apache.org/docs/en/latest/guide/hybrid/plugins/)



## Author

*  **Kuldeep Kumar**