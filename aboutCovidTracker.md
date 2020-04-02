
- Wie sieht das Datenmodell im Backend aus?

/***
<table class="DataModel">
  <tr>
    <th class="DataModel-yw4l"><b>userID</b></th>
    <th class="DataModel-yw4l"><b>userName</b></th>
    <th class="DataModel-yw4l"><b>VName</b></th>
    <th class="DataModel-yw4l"><b>NName</b></th>
    <th class="DataModel-yw4l"><b>location</b></th>
    <th class="DataModel-yw4l"><b>hasCovid</b></th>
  </tr>
  <tr>
    <td class="DataModel-yw4l">0001</td>
    <td class="DataModel-yw4l">Uname1</td>
    <td class="DataModel-yw4l">Vname1</td>
    <td class="DataModel-yw4l">Nname1</td>
    <td class="DataModel-yw4l">32875362.2323</td>
    <td class="DataModel-yw4l">True</td>
  </tr>
  <tr>
    <td class="DataModel-yw4l">0002</td>
    <td class="DataModel-yw4l">Uname2</td>
    <td class="DataModel-yw4l">Vname2</td>
    <td class="DataModel-yw4l">Vname2</td>
    <td class="DataModel-yw4l">99362.23523</td>
    <td class="DataModel-yw4l">Flase</td>
  </tr>
</table>
***/

*******************

- Wie kann ich die App anonym machen? brauche ich Namen?

The name entry is optional, not mandatory, in order to login,
 it is used with a user name chosen by the user.
 
 ******************
 
 - Wie komme ich an die GPS Daten ran?
 
    >navigator.geolocation.getCurrentPosition((e) => {console.log(e)})
  ******************
  
 - Wie berechne ich mit GPS Nähe? Was heißt Nähe? 1m entfernt?
 
 Alles unter 10 m entfernt
  ******************
  
 - Wie kann ist sowas testen ohne GPS zu haben?

using location data and use it to calculate the GSP coordinates