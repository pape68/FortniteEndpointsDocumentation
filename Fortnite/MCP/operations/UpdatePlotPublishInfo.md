# UpdatePlotPublishInfo

**Description**: `Updates the Plot Publish info for a Creative Island` \
**Profiles**: `creative` \
**Note**: `DedicatedServer ONLY`

## Body
```js
{
    "plotItemId": "", //island item (island guid)
    "linkCode": "", //island code, e.g. 1111-2222-3333
    "vkProjectId": "", // valkyrie (creative 2.0) project id
    "vkModuleId": "", //valkyrie (creative 2.0) module id
    "linkVersion": 1, //island version
    "moderationLinkCode": "" // mod island code (only certain islands have it)
}
```
