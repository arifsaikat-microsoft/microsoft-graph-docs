---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const qna = {
  displayName: 'Global Country Holidays',
  webUrl: 'http://www.contoso.com/',
  description: 'The dates that Contoso offices will be closed to observe holidays. These dates may differ from the actual date of the holiday in cases where the holiday falls on a wee​kend.    <table>    <thead>    <tr>    <td><strong>2021 Dates</strong></td>    <td><strong>Holiday</strong></td>    </tr>    </thead>    <tbody>    <tr>        <td>January 1, 2021</td>        <td>New Year\'s Day</td>    </tr>        <tr>        <td>January 18, 2021</td>        <td>Martin Luther King Day</td>    </tr>        <tr>        <td>February 15, 2021</td>        <td>Presidents Day</td>    </tr>        <tr>        <td>May 31, 2021</td>        <td>Memorial Day</td>    </tr>        <tr>        <td>July 5, 2021</td>        <td>Independence Day</td>    </tr>        <tr>        <td>September 6, 2021</td>        <td>Labor Day</td>    </tr>        <tr>        <td>November 25, 2021 - November 26, 2021</td>        <td>Thanksgiving Day and Day after Thanksgiving</td>    </tr>    <tr>        <td>December 23, 2021 - December 24, 2021</td>        <td>Christmas Eve and Christmas Day</td>    </tr>    </tbody>    </table>',
  keywords: {
    keywords: ['new years day', 'martin luther king day', 'presidents day', 'memorial day', 'independence day', 'labor day', 'thanksgiving', 'christmas'],
    reservedKeywords: ['holidays', 'paid days off'],
    matchSimilarKeywords: true
  },
  availabilityStartDateTime: '2020-09-21T20:01:37Z',
  availabilityEndDateTime: '2021-12-31T20:01:37Z',
  languageTags: ['en-US'],
  platforms: ['ios'],
  groupIds: ['groupId'],
  state: 'published'
};

await client.api('/search/qnas')
	.version('beta')
	.post(qna);

```