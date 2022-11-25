Language : English | [中文](./README.zh-CN.md)

<h1 align="center">Hypercrx</h1>

<div align="center">

[![CLA assistant](https://cla-assistant.io/readme/badge/hypertrons/hypertrons-crx)](https://cla-assistant.io/hypertrons/hypertrons-crx)
[![Slack](https://img.shields.io/badge/slack-join_chat-success.svg?logo=slack)](https://join.slack.com/t/hypertrons/shared_invite/zt-1a7tfc1tx-5YP8m59Yg~vSqiMBMeUJnQ)
[![](https://img.shields.io/badge/Data-OpenDigger-2097FF)](https://github.com/X-lab2017/open-digger)

</div>

`Hypercrx` (pronounced: 'Hai-puh CRX') project aims at tracing, digging and gaining insight into the projects and developers you're interested in. We do this by inserting useful dashboards into `GitHub` pages. `Hypercrx` provides an effective way for digital operations and analysis of open source community.

## Install

<img src="https://raw.githubusercontent.com/alrra/browser-logos/90fdf03c/src/chrome/chrome.svg" width="48" alt="Chrome" valign="middle"> [Click here to install Chrome extension](https://chrome.google.com/webstore/detail/hypercrx/ijchfbpdgeljmhnhokmekkecpbdkgabc)

<img src="https://raw.githubusercontent.com/alrra/browser-logos/90fdf03c/src/edge/edge.svg" width="48" alt="Edge" valign="middle"> [Click here to install Edge extension](https://microsoftedge.microsoft.com/addons/detail/hypercrx/lbbajaehiibofpconjgdjonmkidpcome)

For more information please refer to [Installation Guide](./INSTALLATION.md).

## Datasource

`Hypercrx` consumes data that generated by [OpenDigger](https://github.com/X-lab2017/open-digger), which is an open source project that focuses on open source analysis.

## Dashboards 🔥🔥🔥

You can find these dashboards in:

<table>
  <thead>
    <tr>
      <th width="50%">Entrance 1: GitHub User's Profile Page</th>
      <th width="50%">Entrance 2: GitHub Repository Page</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img
          src="https://user-images.githubusercontent.com/115639837/202907271-3eafea52-0dfd-4376-a896-b7ebbd75ae1d.png"
        />
      </td>
      <td>
        <img
          src="https://user-images.githubusercontent.com/32434520/180447103-76ff1e25-ec35-4e7f-bd54-9d98545ca1df.png"
        />
        <img
          src="https://user-images.githubusercontent.com/115639837/202907348-678bfaca-81a0-40b3-a0ee-1e9a4931961b.png"
        />
      </td>
    </tr>
  </tbody>
</table>


### Project Releated

 <table> 
   <thead> 
     <tr> 
       <th width="33%">Project Correlation Network</th> 
       <th width="33%">Developer Collabration Network within Project</th> 
       <th width="34%">Project Activity & OpenRank Trend</th> 
     </tr> 
   </thead> 
   <tbody> 
     <tr> 
       <td> 
         <img 
           src="https://hypertrons.oss-cn-shanghai.aliyuncs.com/images/readme-prn.gif"
         /> 
       </td> 
       <td> 
         <img 
           src="https://user-images.githubusercontent.com/90528630/171819879-d76a3f01-444a-4544-8d46-de539c5684c3.gif"
         /> 
       </td> 
       <td>
         <img 
           src="https://user-images.githubusercontent.com/115639837/202907049-d799bfe1-2bd2-4ef0-a467-cc480c6488eb.gif"
         /> </td>
     </tr>
     <tr> 
       <th colspan="3">Repo Details (hover triggered)</th> 
     </tr> 
     <tr> 
       <td colspan="3"> 
         <img 
           src="https://user-images.githubusercontent.com/32434520/202904112-f0f8386f-582d-4883-8e24-1be437f88ee0.png"
         /> 
       </td> 
     </tr> 
   </tbody> 
 </table> 


- **Project Correlation Network**: Project Correlation Network shows the correlation between projects for a given time period. From this graph you can find the projects that are related to the given project.

- **Developer Collabration Network within project**: Developer Collabration Network within project shows the collaboration between active developers within the project for a given time period. From this graph you can find the active developers in the given project. What's more, you can find the collaborative relationships between these developers.

- **Project Activity & OpenRank Trend**: The Project Activity and OpenRank Trend chart presents how the two metrics evolve since 2015. In the chart, you can zoom and drag using your mouse or touchpad, and you can toggle either of the data by clicking the legend buttons as well.

- **Repo Details**: Trends of Activity, OpenRank, Participants, Fork Events, Star Events, Open Issue Events, Issue Comment Events, Open PR Events, PR Merge Events, Review Comment Events, Merged Addition & Deletion Code Lines.


### Developer Releated

<table> 
   <thead> 
     <tr> 
       <th width="33%">Developer Collabration Network</th> 
       <th width="33%">Developer's Most Participated Repos</th> 
       <th width="34%">Developer's Activity & OpenRank Trend</th> 
     </tr> 
   </thead> 
   <tbody> 
     <tr> 
       <td> 
         <img 
           src="https://user-images.githubusercontent.com/90528630/171820059-96c6da74-3d29-4e79-a08d-a07861682646.gif"
         /> 
       </td> 
       <td> 
         <img 
           src="https://hypertrons.oss-cn-shanghai.aliyuncs.com/images/readme-dmpr.gif"
         /> 
       </td> 
       <td>
         <img 
           src="https://user-images.githubusercontent.com/115639837/202906644-4a22a336-fded-4ef2-82e1-16c3cb749d32.gif"
         /> </td>
     </tr> 
   </tbody> 
 </table> 



- **Developer Collabration Network**: Developer Collaboration Network shows the collaboration between developers for a given time period. From this graph you can find other developers who are closet to a given developer.
- **Developer's Most Participated Repos**: Developer's Most Participated Repos shows the active projects of developers in a given time period. From this graph you can find out the most active repositories for a given developer.
- **Developer's Activity & OpenRank Trend**：The Developer Activity and OpenRank Trend chart presents how the two metrics evolve since 2015. In the chart, you can zoom and drag using your mouse or touchpad, and you can toggle either of the data by clicking the legend buttons as well.

## Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) if you are new here or not familiar with the basic rules of Git/GitHub world.
### Requirements

1. node >= 16.14

2. yarn

### Quickstart

1. git clone https://github.com/hypertrons/hypertrons-crx

2. cd hypertrons-crx

3. yarn install

4. yarn run start

5. Load the freshly built unpacked extension on Chrome following:

   1. Access chrome://extensions/

   2. Check "Developer mode"

   3. Click on "Load unpacked extension"

   4. Select the "build" folder under the project root directory

   5. Keep "service worker" DevTools page open ([why?](https://github.com/hypertrons/hypertrons-crx/pull/274#discussion_r811878203))

      ![](./assets/keep-service-worker-devtools-open.jpeg)

6. Happy hacking!

### HMR & auto-reload

If you are developing Options page or Popup page, each time you save files the pages will hot replace the modules without refreshing, which means you can see the changes right away.

However, if you are developing Background or ContentScripts, each time you save files the service worker will reload the extension automatically. And if you are developing ContentScripts, then pages that injected with ContentScripts will refresh themselves to run the newest scripts.

### Q&A

Any type of contribution is welcome, you can submit [Issue](https://github.com/hypertrons/hypertrons-crx/issues) to report bugs or ask question.

For more information please refer to [Contributing Guide](./CONTRIBUTING.md).

Message us on <a href="https://join.slack.com/t/hypertrons/shared_invite/zt-1a7tfc1tx-5YP8m59Yg~vSqiMBMeUJnQ" target="_blank">Slack</a>.
