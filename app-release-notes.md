# 🚀 How to join Bit.Country Pioneer? 


👉👉 [Visit Bit.Country Pioneer App](https://pioneer.bit.country) 👈👈


### Questions and Supports❓

Joining our [Discord](https://discord.com/invite/PaMAXZZ59N) and official [Telegram](https://t.me/BitCountryOfficialTG)

# ✅ Release Notes

## Pioneer & AlphaTestnet 0.0.1.10 (14-October-2022)

Details
- General
  - Cross-chain XCM asset management
  - Notifications system improvements
- Avatar
  - Updated customizer infrastructure to support new emotes system
- Metaverse
  - Updated loading behavior, updated loading screen, waits for better loading characteristics before fading and shows tips
  - New UI for chat, wallet and metaverse info
  - New network performance indicator, gives rough estimation of network performance
  - New minimap design
  - New UI for multiplayer button
  - Redesigned animations system to support new emotes (emotes coming later)
  - Avatar loading system improved
  - Reduce network calls, and improve efficiency with world streaming
  - Updated asset loading system and infrastructure.
  - Hyperlink tool enabled for metaverses, you can set a link on an asset for users to view. Design not finalised yet
  - Improvements to typewriter tool's rotation system
  - Improvements to performance and memory usage



## Pioneer & AlphaTestnet 0.0.1.9 (07-September-2022)

- Summary
  - Metaverse info - get more insights into a metaverse’s performance with details about how many assets, polycount and more.

Details
- General
  - Pulse page UI improvements .
  - BIT cost applied when creating and updating post and comments.
  - Ability to upload a country logo and the logo will appear on the side bar.
  - UI improvement on different pages, improve the overall visual color contrast, redesign/ improve UX, improve main menu design, and improve the responsive design.
  - Improvement on different components such as alert messages, marketplace cards, dropable areas, and notifications.
  - Updated the overall dark theme on the app.
  - UI improvement on craft NFT page, created 2 UI(2D & 3D viewer) to show different types of craftables, created a filter for NFT Pass and Wearable.
  - Perform testing on different environments, as well as bug fixing and UI improvement.
  - More NSFW filters are applied in different contexts of the Bit.Country platform.
  - Added report asset and share on social media feature for NFTs and marketplace listings

- Marketplace
  - Improved the filter style for the marketplace and added a mobile-friendly filter on the marketplace and improve the mobile view on different pages.

- Map
  - Update the map server to use the same color scheme as the main app, and fixed some of the alignment issues in the map server.
  - Create a CI/CD pipeline for the map server to streamline the deployment process of the map server.
  - Allow anonymous access to the metaverse map for users who want to share their metaverse via URL.

- Avatar
  - Create a UI to craft wearables and implemented a process to streamline Avatar wearables uploads.
  - Added feature for user to redirect to the craft NFT page with a pre-selected wearable if the user clicked the link button from avatar customizer.

- Metaverse 
  - Metaverse info display added to give insights into metaverse performance rating - see details about polycount, meshes and more to get an idea of what might be contributing to poor performance. A useful tool for metaverse owners, builders or users curious about performance.
  - Access restriction toggle for metaverse 3d world - available in the metaverse settings menu, you can prevent users other than yourself from entering the 3d world, can be used while you are still developing your land.
  - New supported voxels, transparency can be added to voxels to create glass or similar materials. Transparency from the texture’s alpha channel added with new use alpha from texture toggle. Fluid option to make a voxel that is transparent and able to be walked through.
  - Other improvements to voxel system to resolve issues in some cases.
  - Removed the ability to scale placed assets in the asset selector. You’ll want to get the scale correct when placing the first time, this is to improve consistency with BIT costs.
  - Updated BIT cost display and calculation on UI.
  - New UI to display current value out of quota value when building, so you can tell how much remains of the quota for your build.
  - Pioneer environment infrastructure, resiliency and more set up for release.
  - Performance improvements when assets move into and out of view distance.
  - Resolved text incorrectly displaying in some areas.
  - Fixed text orientation issue with typewriter.
  - Resolved bugs related to bunker load times, and the vault failing to load in some cases.
  - Updated internals to ease adding new functionality and tooling.
  - Rotation discrepancies between preview, pending and final were resolved.
  - Better messages for logged-out users and better handling in general.
  - Added metaverse name to menu.
  - Smoother voxel movement system when walking up voxels.
  - Improved notifications and in-progress activities.
  - Fix rendering issue causing meshes to be too “shiny”.
  - Improved avatar loading speed.
  - Show loading indicator while skybox is loading.
  - Resolve brightness not always applying depending on configuration on load.
  - General improvements - UX, UI and bug fixes. 


## v0.0.1.8 (12-August-2022) 

- Summary
  - Featured metaverses.
  - Advanced image analysis.
  - Notification Settings.
  - Emergency and maintenance mode.
  - Rendering changes - view distance for assets, quota system and tweaks.

- Details
  - General
    - Token faucet available on site.
    - New and updated tutorials for platform features.
    - Updated image classification system.
    - Fixes and improvements across web and metaverse viewer. 
    - Resolved styling issues, edge cases and more to improve UI and UX.
    - Performance improvement on different pages.
    - Bug fixed for the number of metaverse owners and size on metaverse home page.
    - Removed balance transfer button on site.
  - Marketplace
    - Improved filtering.
    - Listing shareable on social media
    - UI Responsive implementation
  - NFT
    - Implement shareable feature on NFT item.
    - Issue fixed on missing Mint button on different NFT type
    - UI Responsive implementation
  - Map
    - Updated styling for owned land units/estates in other’s metaverses - makes it easier to see your land.
    - Performance enhanced, improve the large loading metaverse such as Kaosland.
    - Disable the menu when the user clicks outside of the metaverse boundary.
    - Cache the geodata and use pagination on the data.
    - Apply NSFW to estate image uploader.
    - Display all estate blocks on the create estate page.
    - Display create/manage menu if you owned a land unit in other metaverse.
  - Avatar
    - UI Improvement and bug fixed
    - Updated customizer to auto-select the main avatar
    - New wearables and wearable category (glasses)
  - Metaverse 
    - Quota system to give metaverse more control over performance and quality. Specify a maximum amount of meshes, polycount and/or file size per land unit - you may want to update your quota settings if you notice some models don’t appear anymore.
    - Build system, better feedback on build completion and rejection.
    - Better player loading performance in heavy metaverses.
    - No props/nfts toggle.
    - Multisided voxel support added, now you can create voxels with different images for top, sides and bottom.
    - Sharing menu item in 3D world for sharing to social media.
    - Updated inputs system, less dependent on keyboard layout.
    - Boundaries between void and land, changed so you can walk through easily.
  - Graphics
    - Updated view distance voxels and assets.
    - Fix anti-aliasing and other effects not applying in all cases.
    - Tooling
    - Asset selector consolidation for asset removal, text removal.
    - BIT costs update, using new cost calculation system.
    - Hide estate improvements, make it clearer when estates are hidden and general process
    - Better feedback for many tools and situations.

## v0.0.1.7 (25-July-2022) 

- Features

  - New home page summary.
  - Wallet and Notification setting.
  - New Estate Customization tool.
  - New Feedback system.
  - New Tutorial and Guideline implementation.
  - 3D Analysis tool.
  - New AlphaNEER faucet claim directly on App.
  - 3D metaverse performance improvements

- Improvements & bug fixes

  - Pioneer spot auction - only accept Metaverse with deployed land block. 
  - Pioneer spot auction - only 1 leading spot per metaverse.
  - Pioneer spot auction - issue with not enough NEER balance.
  - Craft Metaverse Object error on some Metaverse Objects.
  - Multiple crafting in sub second causes on bridge halt.
  - Improve loading speed on Reward History Breakdown in Material campaign.
  - Disable Stake / Unstaking if there is any un-redeem unstaked token.
  - Clearer message only allowing unstaking once per round.
  - New Nickname and Notification settings.
  - Raw Land Block transfer issue fixed.
  - Raw Land Block deployment issue fixed.
  - 3D analyser when creating NFT Collection.
  - Displaying 3D analyser result on NFT/Listing viewer.
  - Collection description text area.
  - Improve Bug Report feature.
  - Make My Land as a separated tab.
  - Pagination implementation on Reward History Breakdown in Material campaign.
  - NFT Report on NFT viewer and listing viewer.
  - NFT reported under local marketplace, will be shown under metaverse setting page for metaverse owner to make decision.
  - Sudo can view all reports related to NFT report, listing report.
  - Display metaverse name at Estate Zoom level on Pioneer Map.
  - Display Your Rank in the BIT Reward Campaign will be available after the next round after staking the first time instead of stake to enable.
  - Estate image upload - burn BIT. 

## v0.0.1.6.1 (28-June-2022) 

Minor improvements:

- General improvements

  - Home page summary
  - Loading speed improvement on Metaverse Home.
  - Loading speed improvement on Global NFT Search.
  - Improve Menu collapse when entering directly to 3D world.
  - Remove blockchain connection on the map to improve loading speed.
  - Material Campaign improvement, claiming reward logic.
  - Add confirmation modal when authorizing, rejecting and removing collection in metaverse settings

- Pioneer Map

  - Estate layer drawing on Pioneer map.
  - Deploy Raw Land Block or Subdivision will also update Pioneer Map.
  - Added a follow btn/ function on the pioneer map
  - Added, home, view map, view metaverse, view Pulse and marketplace on the quick actions section on the pioneer side menu
  - Improved the drawing performance for the pioneer map and land block map
  - Added feature to redraw(update) the pioneer map when a metaverse map is updated(also on the pioneer map).
  - Added feature to stage the drew image. (the map will not show in broken if its updating, instead the map will be updated once all tile images are drew)
  - Updated the UI on all maps
  - Fixed mini map coordinate issue.
  - Fixed refresh feature on maps

- Metaverse
  - Clicking connect to multiplayer will be blocked if logged on
  - Chat tabs, block renamed to global
  - Default settings set to low for new users
  - Low, Medium and High presets for settings have lower overall quality compared to before
  - Player avatars don’t all play same animation in multiplayer

- Marketplace
  - Metaverse filter was not working in collections view (Global NFT Search, Local Marketplace)
  - Bundle not showing correctly from home page (Local Marketplace)
  - Filter metaverse throwing error in Global NFT Search

- My Assets
  - Metaverse object nft details page image was not showing
  - Show disabled main price input (on the right) when selling Estate or Bundle.
  - Immediate update when transfer or list NFT with quantity.
]
- Create Metaverse
  - Display Network fee when creating metaverse
  - Refresh metaverses side menu when creating a new metaverse
  
## v0.0.1.6 (21-June-2022)

Release summary:

- Pioneer Map feature
  - Multi-metaverse map protocol.
  - Allow spot issuance, auctioning and securing the spot.
  - Pioneer Map Viewer.
- Multiple Land Block deployment improvement.
- Global NFT Search improvement
- Bundle item 
- Wallet format transformation
- Implemented NFT Hard Limit, strict minting if Hard Limit set.
- More wearable implementation.
- New Bug Report Tool supports built-in screen capture and recording.
- Bundle Royalty fee collection improvement 

Details:

- Moved reset filter to the Search section
- Switching to a metaverse that you don't own no longer displays the notification "Welcome to Metaverse”
- Deposit/Withdraw/BIT Transfer wallet format and perform verification
- Bundle creation and selling simple validation check
- Bundle on global marketplace opening individual item
- Remove item from the bundle.
- Improve Error message on blockchain transaction.
- Performance enhancements - greatly reduced GPU usage across a variety of situations
- Memory use enhancements and load speed - reduced memory usage related to multiplayer and improve load speed in some cases
- Improved UI checks to prevent invalid build requests from trying to submit
- Improved error messages related to build requests, asset placements and more
- Improved backend handling of erroneous builds, added more checks to investigate any remaining edge cases.
- Updated backend to prevent edge case related to multiple submissions close together - you'll need to wait up before starting another build request (could be up to a minute but often less than 15 seconds).
- Reduced some default graphical settings to give a better experience to new users.
- Improved graphical experience, appearance, between settings
- Improve support for login while already in the world
- Voxel pack API and UI to separate blocks into separate packs - packs can have at most 64 blocks (at present), and you can have up to 7 separate packs (not including the default pack, which would be 8 in total)
- Estate hiding tool - allowing metaverse owners to hide questionable estates from users in case of violation of community terms, will be rolling out soon after deployment
- Improved multiplayer server robustness and related messaging to user
- Updated bounds checks and related messaging when placing assets
- Design and implement Pioneer Map UI and UX.
- Added focus feature on the map where you can click on the spot and you can focus on that area.
- Improved Pioneer Map performance and scalability by using a queue system.
- Improved Pioneer Map drawing performance by implementing a cache system.
- Allow user to enter specified coordinate into dimension by using right click menu and drag and drop the locator into the map.
- Updated the default size of the materverse to a maximum of 3600 land units.
- Improved Responsive UI of Avatar Customizer.


## v0.0.1.5 (1-June-2022)

Release summary
* Metaverse Estate features - deploying land blocks, creating estates, building in the metaverse.
* Metaverse settings.
* Metaverse client graphics setting menu - configure the graphical quality to suit your device.
* Bundle NFT Support.
* Metaverse Listing Fee implementation.
* Notification System beta-v.0.0.1.5.

Details

* Release Raw Land Block (deployable land block for your metaverse) on the blockchain.
* Release Estate and Land Units on the blockchain.
* Support Raw Land Block on the Marketplace.
* Support Estate and Land Units on the Marketplace.
* Support Estate and Land Unit bundle on the Marketplace
* Create a Bundle Listing for your NFTs
* Raw Land Blocks can now be purchased via Global NFT Search
* View Estates and Land Units on your My Assets page
* Sell and transfer Estates and Land Units
* Filter NFTs by NFT Type in the local marketplace and Global NFT Search
* Metaverse Home
* Metaverse settings - add/update social links to Metaverse
* Metaverse settings - add/update Listing Fee for local Marketplace
* Metaverse settings - ability to change the metaverse display name
* Notification System - users will now receive notifications regarding some of the existing events.
* Collection NFT Class Fund - users can now see the available funds under my assets -> collection and withdraw.
* Displaying network fees for transactions if applicable.
* Local Marketplace activities to track all trading transactions.
* Metaverse access - you can now enter your own metaverse.
* Metaverse Estate building - requesting build permissions, placing/editing voxels, placing/editing/replacing/removing assets in the metaverse.
* Metaverse Permisisons - detection of transfer of estate related to build permissions.
* Graphics Settings - adjust graphical settings as appropriate for your device, enable/disable/configure post processes, shadows, rendering quality and more.
* Updated quick start guide to include more information.
* Metaverse Estate build area - visualize buildable area when inside build mode.
* Updated BIT calculation system - more accurate, you can trigger the calculation on demand.
* Updated environment customizer system - new menu for accessing and changing sun settings.
* Add new terms and conditions to create prop, etc.
* Updated Bunker to include vault.
* Improved gravity system - better experience inside bunker on stairs and more.
* Autostep feature for voxels.
* Include details about current BIT Spot balance, so it’s easier to see your balance.
* Include notice message about pending Polkadot js transactions.
* Keep advanced position after placement, make it easier to place multiple assets.
* Updated menu inside metaverse worlds - access settings and build menu, and leaving the client.
* Bug fixes and improvements across many tools for UI and UX in metaverse worlds.


## v0.0.1.4 (10-May-2022)
Release summary
- Bunker - your personal space storing your own assets.
- Showroom - metaverse version of your local market place
- NFT - Royalty fees, Batch listing / transfer, favourite, trading activities, multi-types of NFT.
- Avatar - Skin color and performance improvement
- Sandpit - All outstanding bugs are fixed. Sky - more sky templates
- Various improvements. Please see details below

Details
- Stabilized asset gateway for depositing and withdrawing BIT.
- Support royalty fee for NFT Creator, earn royalty fee for each transaction on the local marketplace.
- Migrate the existing NFT collection to set the default royalty fee.
- Implement minting fee when minting collection and NFT. 
- Improved My Assets page with filters to show purchased, created, listed, auction bids and favorites
- Users can favorite listings and non-listed assets so they can be viewed later in the my assets page
- Only allow metaverses with the Global NFT Search Crafted NFT to be able to list NFTs and collections in the Global NFT Search page. 
- Added a new section in the NFT listing page to see other auction/buy now listings of the same nft
- Added batch listing and transfer feature for multiples of the same nft
- Support new NFT types PDF, MP4, OGG
- Users can now see a list of the Metaverse followers
- Added activities tab under the collection page with filters
- User can click an activity item to see details page
- Displaying floor/ceiling price and volume traded for collections
- Added a “Go Back” functionality to the collection page
- Metaverse Settings page Global NFT Search option integrated
- NFT Authorization implemented. User will need to craft object and enable the feature to view collection listing requests
- One wallet, one account - if the user wants to switch wallets while logged in, they will need to authorize and link the new wallet -> sign process.
- Separated functionality for Metaverse Utility and Wallet Utility
- Released Bunker
  - Includes new model for bunker
  - Includes other environmental changes
  - Updated and improved block build handling
  - Updated and improved asset placement
- Fixed edge case with cancellation not restoring blocks
- Added pending preview for placed assets
- Improved asset preview resolves some model display issues
- Improved inputs on all tools
  - Resolved manual input errors on some inputs – e.g. couldn’t type 1.1 but only type 1
  - Resolved edge case where scaling broke aspect ratio for media items
  - Resolved rotation resetting on typewriter when changing scale
- Added close contextual button to tools to improve UX
- Resolved error on some skybox types
- Resolved error on some block and asset uploads
- Improvements to much of the UI to improve snappiness and more
- Improved advanced placement behaviour on all tools
- Improved API
  - Resolved edge cases when placing assets, texts and other items
  - Improved handling of block submissions – faster handling
- Updated lighting and configuration for graphical settings
- Resolved edge case behaviour related to collision detection toggling
- Improve edge case when creating some new skyboxes, blocks and models in ui
- Improve shadows for player, clothing and world
- Added 3D showroom to display the NFT in the marketplace.
- Improve the UI responsive of the avatar customizer
- Improve the Avatar skin color changing UI.
- Allow user to change their skin color back to the original skin.
- Allow user to reset their avatar wearable while editing the wearable.
- Reuse existing resources if they existed in the local environment instead of fetching the new item.
- Show warning when closing tab/window with unsaved changes
- Updated cost calculation for assets and models
- Allow environment customizer changes to persist in sandbox

## v0.0.1.3

- 2057819 Enhance asset selector and builder
- 72d0c90 Merge branch 'development/Master' into improvement/AssetSelectorAndBuilder
- 87776f6 Update ordering to add mesh to scene.
- 25e589d Add early break to retries wrapper.
- 356ac5b Display error notification
- 21740d3 Add different error message wording
- 9103cb7 Merge branch 'improvement/AssetSelectorAndBuilder' into development/Master
- bd8d63c Add new bunker.
- 807731e Calculate origin point using bounding box for highlighter
- cc484d6 Avoid adding origin offset everytime we show highlighter
- 88e9c5a Improve pending asset placement
- db8249f Merge branch 'development/Master' into improvement/AssetSelectorAndBuilder
- 64ce6db Revert change on scale Z
- d4d29bd Set rotation for preview mesh.
- b3b752d Fix collision issue
- e772371 Merge branch 'improvement/AssetSelectorAndBuilder' of into improvement/AssetSelectorAndBuilder
- c4171e3 Change to use bounding box unparented from mesh.
- 00153b0 Fix inability to type a value into scale and rotation.
- edc558c Fix error when clicking cancel after advanced placement
- 4884043 Update selected box after cancelling edit
- 9379df9 Fix issue with failure to load preview in model builder.
- d87f73d Migrate changes from placement context in asset selector to model builder.
- 7a1838a rename Spot to On-platform
- 9fa6b25 Fix error in same cases after placing a model from advanced placement
- 9b4cbaf Fix number as string
- 6782675 Add conditional for handling non-model meshes in pending meshes for model builder.
- a2fe3df reverse spot renaming
- 974cb94 Resolve edit issues after changing original scale value
- aa4246a Merge remote-tracking branch 'origin/development/Master' into improvement/AssetSelectorAndBuilder
- 43ba11e Reword from spot to on-platform
- 498bb4f Add quick change to allow other bunkers
- 470ee6d Fix pending mesh placement as per Vuk's work on other branch.
- 7fc4de4 Use latest bunker model.
- 7fa7a1a Add nft/listing favorites feature
- 3c2958c auction display improvements
- 23a3353 Remove double-slash on tutorial image src
- 37b5702 Merge branch 'development/Master' into uat/Master
- d00971d Fix incorrect pending mesh preview placement
- defed09 Ensure we exit check early for other bunkers
- fa312db Fix incorrect pending mesh preview placement
- 214766d Ensure we exit check early for other bunkers
- 8caa961 Merge branch 'development/Master' into uat/Master
- e35770d Is Admin Feature added in the UI
- 3ebbfd0 Minor button style changed
- 909c5d0 Merge remote-tracking branch 'origin/development/Master' into ELEMENT_MATRIX
- 8db95b5 Merge pull request #296 from bit-country/ELEMENT_MATRIX
- 5db2106 Publish Draft tidyup
- 6b4446b Merge pull request #297 from bit-country/ELEMENT_MATRIX
- 0ee7541 update btn style
- 0d4ab62 update showroom style
- f6b6bc5 update avatar customizer style, typos;
- fb27f61 Listing component improvements
- 6dfa7ef remove debugger
- 4a9bdd0 added online model in bunker
- d614bc2 temp disabled sectorHide to show other avatars
- 3e5f98d merge from dev/Master
- 92f7e00 Merge pull request #298 from bit-country/development/Master

## v0.0.1.2 @ 22-Apr-2022

- 2c9f6e0 Improvements left menu metaverses showing all metaverses and scrollable
- 3169c3d Fix Withdraw Bit validation bug
- 23550d7 handle close modals for deposit and withdraw, fix antd hover input error color
- 2b15211 Menu Highlight on marketplace
- 9103425 Minor UI changes
- 71b4c91 Create Metaverse Object initial
- 003b8f9 Update Modal UI, Fixed some richMediaTool bugs, Fixed NFT trigger position issue
- 42411f1 handle transfer validation onBlur, change error message
- 6ed3052 Draft Feature
- a4c2adc Small issue on removing item from grid
- 618d224 fix bid and buy now, git merge issue
- 571bbc9 Fix grammer
- 77b8bd0 Add bounds to sandpit.
- d0d293c Update MiningRate.js
- 76f25f2 Add meshes to show boundary in sandpit
- 43dcc93 Stop building out of bounds for voxels
- 0124fc1 Update environment customiser to keep state in sandpit
- 873568a Fix ordering for setting environment in customiser.
- 41b48e0 remove global styling change for input background in case of conflicts
- 0f0229d Responsiveness of Wallet
- 9b43b4c Feature Setting & NFT Collection Utility
- e2519e7 bit campaign responsiveness
- e8d41d4 Move block selector to avoid contexts drawing over the menu
- 2cdabf0 Prevent leaving page with pending changes.
- fc8d0a5 Update wording
- 7d28d88 Include deposit event to tx history
