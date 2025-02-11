<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

*   [alliances][1]
*   [corps][2]
    *   [Parameters][3]
*   [icon][4]
    *   [Parameters][5]
*   [info][6]
    *   [Parameters][7]
*   [contacts][8]
    *   [contacts][9]
        *   [Parameters][10]
    *   [labels][11]
        *   [Parameters][12]

## alliances

List all active player alliances.

Returns **[Array][13]<[number][14]>** A array of all active player alliances.

## corps

Get all current member corporations of an alliance.

### Parameters

*   `allianceID`  
*   `ID`  {number} The alliance ID to get the alliances from.

Returns **[Array][13]<[number][14]>** The alliances in the alliance.

## icon

Get the icon urls for a alliance.

### Parameters

*   `allianceID`  {number} The alliance ID to get the icon of.

Returns **[object][15]** Links to the different sizes of the alliance icon.

## info

Get public information about an alliance.

### Parameters

*   `allianceID`  
*   `ID`  {number} The alliance ID to get info from.

Returns **[object][15]** Public info on the alliance.

## contacts

### contacts

Get alliance contacts.

#### Parameters

*   `allianceID` **[number][14]** 

Returns **[JSON][16]** 

### labels

Get alliance contact labels

#### Parameters

*   `allianceID` **[number][14]** 

Returns **[JSON][16]** 

[1]: #alliances

[2]: #corps

[3]: #parameters

[4]: #icon

[5]: #parameters-1

[6]: #info

[7]: #parameters-2

[8]: #contacts

[9]: #contacts-1

[10]: #parameters-3

[11]: #labels

[12]: #parameters-4

[13]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array

[14]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[15]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[16]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/JSON
