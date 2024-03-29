# Record TV Request API 

| Element | Description | Type | Required | Notes |
| ---- |---- | ---- | ---- | ---- |
| recordTV | top level | TV program data | Required | |
| &nbsp; &nbsp; date | date of program | *string* | Optional | **default:** use today's date |
 | &nbsp; &nbsp; format | time format | *number* | Optional | **Format:** HH:MM <br /> **Attribute Values:** `24` or `12` <br /> Note: 12 hour format follwed with *AM* or *PM* |
 | &nbsp; &nbsp; duration | total time to record | *number* | Required | in hours |
 | &nbsp; &nbsp; channel | channel to record| *number* | Optional | **default:** use today's date |


# Record TV Request API with attribute Column

| Element | Attribute | Description | Type | Required | Notes |
| ---- |---- | ---- | ---- | ---- | ---- |
| recordTV | |top level | TV program data | Required | |
| &nbsp; &nbsp; when | | date, start time  & format of program |  | Required | |
| | date |  date of program | *string* | Optional | **Format:** YYYY:MM:DD <br /> **default:**  todays date |
| | time |  start time of program | *string* | Required | **Format:** HH:MM 
| | format |  time format | *number* | Required | **Values:** `24` or `12` <br /> 12 hour format follwed with *AM* or *PM* |
 | &nbsp; &nbsp; duration | hours | total time to record | *number* | Required | in hours |
 | &nbsp; &nbsp; station channel |  | channel to record | *number* | Required | |

![](http://damien.pobel.fr/images/youtube-video-github.gif)
![](https://github.com/NimaVibeVans/test/blob/master/giphy.gif)


<figure class="video_container">
  <video controls="false" allowfullscreen="false" >
   <source src="test/blob/master/coverr-jumping-shoes-1561724651038.mp4" type="video/mp4">
    </video>
</figure>


