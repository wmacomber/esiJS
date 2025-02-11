<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

*   [getSettings][1]
*   [setSettings][2]
    *   [Parameters][3]
*   [sleep][4]
    *   [Parameters][5]

## getSettings

Gets the settings for esiJS.

Returns **[JSON][6]** A JSON object with the settings.

## setSettings

Sets the settings for esiJS.

### Parameters

*   `$0` **[Object][7]** 

    *   `$0.route`   (optional, default `"latest"`)
    *   `$0.authToken`  
    *   `$0.language`   (optional, default `"en/us"`)
    *   `$0.projectName`  
*   `route` **[string][8]** Any of the valid routes through ESI. Defaults to `latest`.
*   `authToken` **[string][8]** A valid auth token.
*   `language` **[string][8]** A valid language code. Defaults to `en/us`.
*   `projectName` **[string][8]** The name of your project, used by esiJS to pass in as a header. If not defined, defaults to `esiJS-v${version}`.

Returns **[Boolean][9]** `true` if it was able to sucessfully write. Otherwise, a error.

## sleep

Pause execution of code for a specified amount of time.

### Parameters

*   `millis` **[number][10]** The time to delay (in milliseconds)

Returns **[Promise][11]<[function][12]>** 

[1]: #getsettings

[2]: #setsettings

[3]: #parameters

[4]: #sleep

[5]: #parameters-1

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/JSON

[7]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[8]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[9]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean

[10]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[11]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise

[12]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function
