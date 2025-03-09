## Srikanth

-   bug fixes (5 of them) => code review
-   apply shown on new report
-   measure with same name not shown in list
-   make histogram and metric list call independant of each other
-   make entire query row clickable instead of just the plus icon
-   Loader UI

-   mobile view => code review
-   vite => code review

## Bhavin

-   nv samurai discussion with db team
-   eradicate duplicate dropdowns => partialy done(heatmap is remaining)
-   universal search => prototyping and product discussion

## Sabarni

-   grid layout & resize observer => on hold since sabarni is on leave

## Todo

0. no viewport dimension
1. Grid Layout
2. Resize Oberser

# Must Have Improvements

11. Immutable to rtk
12. PWA?
13. IndexDB
14. NO CLASS BASED COMPONENTS
15. Typescript
16. scss to Tailwind

17. Remove Small Dependencies like react-select, listwrapper, copytoClipboard, react-notif etc; Package.json can be cleaner
18. GA (use GTM mostly everywhere)
19. Better UI for validation flow maybe using blade
20. Unit Tests or something?
21. z-index battle and position absolute
22. Dialog and Popovers using PopoverAPI and native dialog
23. Semantic HTML
24. Saga to rtk?

## Pitching to product

-   Remove the arrow keys in chart legends and dashboard horizontal scroll
-   Headway to featureBase
<!-- OOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO -->

# Apply Issue

1. onDrop on SaveGroupDim why?

# Much Needed

## backlog

1. applyEnabled should match prev query instead of setting it true based on event; temp patch for navigating via sidebar planned
2. selection issue not remembering anymore; now needs some refactor and usage of SamuraiMonorepo
3. Table number rows
4. PlusIcon for full row
5. Sidebar to reports/namespace route
6. json_decode fails for large konom response
7. histogramMeasure icon height
8. EventToggler
9. check all 3 iframes on both reports.mn and access.mn (something is broken ; reported issue)
 <!-- 10. histogramDimensions and then measures call (waterfall) -->
10. Vanilla Laravel; No HMVC, as composer install is breaking right now

# Maybe with Front End Upgrade

0. no viewport dimension
1. z-index battle and position absolute
2. Grid Layout
3. Resize Oberser
4. Semantic HTML
5. Dialog and Popovers using PopoverAPI and native dialog
6. Remove Small Dependencies like react-select, listwrapper, copytoClipboard, react-notif etc; Package.json can be cleaner
7. Headway to featureBase

# Must Have Improvements

10. NO CLASS BASED COMPONENTS
11. PWA?
12. IndexDB
13. GA (use GTM mostly everywhere)
14. Immutable to Immer
15. Saga to rtk?
16. scss to Tailwind; Theme Standardized: spacing, colors, shadows etc
17. Dark mode
18. DropPanelListContainer and related
19. Measures and Dimensions and Tables and related

# more

6. Typescript
7. Unit Tests or something?
8. Better UI for validation flow maybe using blade
9. notif ui custom?; sound on Apply ?
10. Loader UI
<!-- fddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd -->

#### MOVETABLE

# Move Table Improvements

textIndependent gradient
table tile tooltip
dont persist on cancel
ellipsize

# General

Draggable List Item and around it dragSource
DropPanel and DPItem (dropArea)
completely remove ellipsize wherever not needed

# rebasing

header styles

# Srikant

reportName Tooltip

## ask srikant ; why clientFilterTooltip is fixed, 3 resize observer can be 1

<!-- fddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd -->

# p1

initial Scale to 1
responsive file delete; html font size to 100% for all screens(use % over px)
Dashboard one below another
sidebar full page now, also dashboardlist and savedReportList collpased as default
Hide => SUGGESTIONS, leftpanel, rightpanel, changelogIcon, reportName, fullscreen and share from toolbar , plus marking, eventToggler, pinColumns
wrap viewSwitcher Options
Remove padding L and R from viewarea
hover icons for actionHeader and DropPanelitem
new view in siteHeader which hides toolbar and 'FIlter' in mobile view and new layout for Site Header
remove unnecessary div
SHAREURL SLIDER with Overlay Component
disable PinColumns for isMobile
Table: from Table and ::before
temp: postcss for dev mode

# doubts

sidebar animation
onApply mount animation glitch
random media queries
hover icons of other listItems
linked stylesheet's px to rem how??
containerStyles ( also viewSwitcher breakpoints)

# move table

text length independent gradient
ellipsize is useless
draggable list item thing too can be better
DND remove??
dropPanel and plus Icon can do better

# P2 ISSUES

## vite:

marking switcher active icon is not white anymore
(live issue) marking switcher while pressing dot, no autofocus
dumbo linchart gridlines

(canIgnore) Modal : z index issue, should be removed if collapsible menu is refactored

<!-- fddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd -->

<!-- fix filter include dropdown(dev mode issue for select library) -->

# short term

1. dashboardheader sticky
2. charts height of dashboardtile maybe full so that no scroller is there

pinColumns is a container Query implementation

customMeasure dialog toggles right section why the fuck
stringFilter api call unnecessary

# draft

# Draft

1. Server Time Issue: webWorkers, customHooks, fixed without webWorkers; other serviceWorkers
2. Empty Dashboard Clone Issue:
3. Table Header time not in sync with selected timezone: ;not fixed here correctly
4. make GroupDimensions Draggable: react-dnd
5. histogramUrl share issue: ; crappy samurai Monorepo in typescript
6. copyUrl format issue: copy must be text , not color and size in word's paste; not fixed in one go
7. fix csv format: Carbon
8. copy fix: fixed here properly
9. scheduled report for access.mn: not yet fixed at all (all 3 urls for both domains in env)
10. AEST timezone support: monorepo publish
11. shareUrl in a tag
12. containername in env and docker compose
13. LineChart tooltip timezone issue
14. Backend upgrade
15. upgrade fix divide by zero
16. upgrade fix report schedular break after upgrade
17. Kafka logging
18. fix that Fucking Table Header issue this time
19. kafka fix: rename nginx request id
20. update logging and reach out docs: still stale
21. persist threshold while switching report view
22. failed mobile view
23. acl Beta fix
24. collapse sidePanel by default
25. lineChart touch integration
26. minor setup changes
27. increase chart readability
28. move table inside
29. fix chart colors to old
30. hotfix that created another issue: so reverted
31.
