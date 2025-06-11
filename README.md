<opr-view-explorer-tree style="position: absolute; left: 0; top: 0; right: 0; bottom: 0; display: block; overflow: hidden" show-view-selector="true" show-selection-checkmarks="false" show-ci-search="true" show-ci-statuses="oprViewExplorerCtrl.showCiStatuses" on-show-context-menu="oprViewExplorerCtrl.showContextMenu(contextMenuConfig)" collapsible-view-selector="oprViewExplorerCtrl.collapsibleViewSelector" multi-selection="true" invert-preserve-selection="false" api="oprViewExplorerCtrl.viewExplorerApi" recently-used-view-list="oprViewExplorerCtrl.recentlyUsedViewList" item-actions="oprViewExplorerCtrl.itemActions" reserved-toolbar-width="80" class="ng-scope opr-view-explorer-tree"><div opr-resize-detector="oprViewExplorerTreeCtrl.toolbarLayout.onToolbarResize(width)" style="width: 100%; position: relative;" id="oprViewExplorerTree_0" class="ng-isolate-scope"><div class="erd_scroll_detection_container erd_scroll_detection_container_animation_active" style="visibility: hidden; display: inline; width: 0px; height: 0px; z-index: -1; overflow: hidden; margin: 0px; padding: 0px;"><div dir="ltr" class="erd_scroll_detection_container" style="position: absolute; flex: 0 0 auto; overflow: hidden; z-index: -1; visibility: hidden; width: 100%; height: 100%; left: 0px; top: 0px;"><div class="erd_scroll_detection_container" style="position: absolute; flex: 0 0 auto; overflow: hidden; z-index: -1; visibility: hidden; inset: -16px -15px -15px -16px;"><div style="position: absolute; flex: 0 0 auto; overflow: scroll; z-index: -1; visibility: hidden; width: 100%; height: 100%;"><div style="position: absolute; left: 0px; top: 0px; width: 404px; height: 41px;"></div></div><div style="position: absolute; flex: 0 0 auto; overflow: scroll; z-index: -1; visibility: hidden; width: 100%; height: 100%;"><div style="position: absolute; width: 200%; height: 200%;"></div></div></div></div></div></div>

<opr-horizontal-layout spacing="4px" class="btn-toolbar no-padding ve-toolbar ng-scope opr-horizontal-layout"><div class="opr-horizontal-layout-container">
  <!-- ngIf: oprViewExplorerTreeCtrl.extraLeftPadding -->
  <opr-horizontal-layout-item width="283px" class="ng-scope opr-horizontal-layout-item expanded" style="width: 283px; min-width: 283px; border-left: 4px solid transparent; border-right: 4px solid transparent;">
    <opr-reveal-panel ng-show="oprViewExplorerTreeCtrl.showViewSelector" label="Select a view" icon-url="/topaz/static/ODB/images/citypes/icons/view1/view1_16.png" popup-width="283px" popup-height="auto" popup-horizontal-align="right" focus-on-reveal="opr-search2 input" reveal="oprViewExplorerTreeCtrl.revealViewSelector"><button class="btn btn-secondary btn-icon-only reveal-button" title="Select a view" ng-style="oprRevealPanelCtrl.revealButtonStyle" ng-click="oprRevealPanelCtrl.revealButtonClick()" id="" style="visibility: hidden;">
  <!-- ngIf: oprRevealPanelCtrl.icon -->
  <!-- ngIf: !oprRevealPanelCtrl.icon --><i ng-if="!oprRevealPanelCtrl.icon" class="qtm-font-icon qtm-icon-default ng-scope" ng-style="{'background-image':'url(/topaz/static/ODB/images/citypes/icons/view1/view1_16.png)'}" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/view1/view1_16.png&quot;);"></i><!-- end ngIf: !oprRevealPanelCtrl.icon -->
</button>
<div class="opr-reveal-panel-popup" ng-class="{'drop-shadow': oprRevealPanelCtrl.popupDropShadow === 'true'}" ng-style="oprRevealPanelCtrl.popupStyle" style="visibility: visible; width: 283px; height: auto; left: 0px; top: 0px;">
  <ng-transclude>
      <opr-search2 id="oprViewExplorerTree_0_viewSelector" class="ve-view-selector ng-pristine ng-valid ng-scope ng-isolate-scope opr-search2 ng-not-empty ng-touched" mode="dropdown" item-source="oprViewExplorerTreeCtrl.availableViews" ng-model="oprViewExplorerTreeCtrl.viewSelectorSelectedView" placeholder="Select a view" item-height="32" has-focus="oprViewExplorerTreeCtrl.viewSelectorHasFocus" ng-keydown="$event.stopPropagation()" min-visible-item-count="5" max-visible-item-count="20" highlight-placeholder="true" recently-used-item-list="oprViewExplorerTreeCtrl.recentlyUsedViewList" recently-used-max-length="5" popup-width="oprViewExplorerTreeCtrl.popupWidth" select-pre-check="oprViewExplorerTreeCtrl.selectPreCheck()" style=""><div class="table opr-search2-panel" id="oprSearch2_0" ng-class="{'search-mode': oprSearch2Ctrl.mode === 'search', disabled: oprSearch2Ctrl.disabled}" selected-item-id="ECommerce Servers_ Copy" title="ECommerce Servers_ Copy" ng-mousedown="oprSearch2Ctrl.controlMouseUpDown($event)" ng-mouseup="oprSearch2Ctrl.controlMouseUpDown($event)">

  <div class="table-row">
    <div class="table-cell opr-search2-item-icon-cell ng-hide" ng-show="oprSearch2Ctrl.showItemIcons &amp;&amp; oprSearch2Ctrl.result.getSelectedItem().iconUrl">
      <div class="opr-search2-item-icon" ng-attr-style="background-image: url({{oprSearch2Ctrl.result.getSelectedItem().iconUrl}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/view1/view1_16.png)">
      </div>&nbsp;
    </div>

    <div class="table-cell opr-search2-input-cell" style="width: 100%">
      <input tabindex="0" id="oprSearch2_0_input" class="opr-search2-input  highlight-placeholder ng-not-empty ng-touched" ng-class="{'highlight-placeholder': oprSearch2Ctrl.highlightPlaceholder === 'true'}" placeholder="Select a view" autocomplete="off" aria-autocomplete="none" ng-disabled="oprSearch2Ctrl.disabled" ng-focus="oprSearch2Ctrl.onControlFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)" ng-keydown="oprSearch2Ctrl.inputKeyDown($event)" ng-mouseup="oprSearch2Ctrl.inputMouseUp($event)" ng-mousedown="oprSearch2Ctrl.inputMouseDown($event)" ng-model="oprSearch2Ctrl.searchTerm" opr-select-on-focus="" style="">
    </div>

    <div class="table-cell opr-search2-result-count-cell ng-binding ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.result.getSelectedItem()" id="oprSearch2_0resultCountCell" data-selected-item-index-and-total-items="1 of 2">
         1 of 2
    </div>

    <div class="table-cell opr-search2-button-cell prev btn-toolbar no-padding ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.result.getSelectedItem()">
      <button class="prev btn btn-secondary" ng-focus="oprSearch2Ctrl.onControlFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)" ng-click="oprSearch2Ctrl.result.setSelectedItemIndexRelative(-1)" title="Move Up">
        <i hpe-svg-icon="" class="opr-search2-search-icon qtm-icon-up--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<polygon points="2.6,7.6 3.4,8.4 8,3.7 8,15 9,15 9,3.7 13.6,8.4 14.4,7.6 8.5,1.8 "></polygon>
</svg>
</i>
      </button>
    </div>

    <div class="table-cell opr-search2-button-cell next btn-toolbar no-padding ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.result.getSelectedItem()">
      <button class="next btn btn-secondary" ng-focus="oprSearch2Ctrl.onControlFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)" ng-click="oprSearch2Ctrl.result.setSelectedItemIndexRelative(1)" title="Move Down">
        <i hpe-svg-icon="" class="opr-search2-search-icon qtm-icon-down--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<polygon points="14.4,8.4 13.6,7.6 9,12.3 9,1 8,1 8,12.3 3.4,7.6 2.6,8.4 8.5,14.2 "></polygon>
</svg>
</i>
      </button>
    </div>

    <div class="table-cell opr-search2-dropdown-icon-cell ng-hide" ng-show="oprSearch2Ctrl.isInDropdownMode() &amp;&amp; oprSearch2Ctrl.popupVisible" ng-click="oprSearch2Ctrl.dropdownIconClick('close')" style="">
      <div class="opr-search2-dropdown-icon-container open">
        <!--<div class="opr-search2-dropdown-icon">.</div>-->
        <div class="caret"></div>
      </div>
    </div>

    <div class="table-cell opr-search2-dropdown-icon-cell" ng-show="oprSearch2Ctrl.isInDropdownMode() &amp;&amp; !oprSearch2Ctrl.popupVisible" ng-click="oprSearch2Ctrl.dropdownIconClick('show')" style="">
      <div class="opr-search2-dropdown-icon-container">
        <div class="caret"></div>
      </div>
    </div>

    <div class="table-cell opr-search2-search-icon-cell ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; (!oprSearch2Ctrl.searchTerm || (oprSearch2Ctrl.searchTerm.length === 0))">
      <div class="opr-search2-search-icon-container" ng-click="oprSearch2Ctrl.searchIconClick()" title="Search">
        <i hpe-svg-icon="" class="opr-search2-search-icon qtm-icon-search--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<path d="M15.354,14.646L10.577,9.87C11.463,8.825,12,7.475,12,6c0-3.309-2.691-6-6-6S0,2.691,0,6s2.691,6,6,6
	c1.475,0,2.825-0.537,3.87-1.423l4.776,4.776L15.354,14.646z M6,11c-2.757,0-5-2.243-5-5s2.243-5,5-5s5,2.243,5,5S8.757,11,6,11z"></path>
</svg>
</i>
      </div>
    </div>

    <div class="table-cell opr-search2-clear-icon-cell ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.searchTerm &amp;&amp; (oprSearch2Ctrl.searchTerm.length > 0)">
      <div class="opr-search2-clear-icon-container" ng-click="oprSearch2Ctrl.clearIconClick()" title="Clear">
        <i hpe-svg-icon="" class="opr-search2-clear-icon qtm-icon-search-cancel--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<path d="M8.7,8l5.6-5.6c0.2-0.2,0.2-0.5,0-0.7s-0.5-0.2-0.7,0L8,7.3L2.4,1.6c-0.2-0.2-0.5-0.2-0.7,0s-0.2,0.5,0,0.7L7.3,8l-5.6,5.6
	c-0.2,0.2-0.2,0.5,0,0.7c0.1,0.1,0.2,0.1,0.4,0.1s0.3,0,0.4-0.1L8,8.7l5.6,5.6c0.1,0.1,0.2,0.1,0.4,0.1s0.3,0,0.4-0.1
	c0.2-0.2,0.2-0.5,0-0.7L8.7,8z"></path>
</svg>
</i>
      </div>
    </div>

    <!-- ngIf: oprSearch2Ctrl.buttonActions && oprSearch2Ctrl.buttonActions.length > 0 -->

  </div>
</div>

<div class="opr-search2-popup" style="display: none; width: 343px; top: 100%; bottom: auto;">
  <div class="opr-search2-popup-items-panel" id="oprSearch2_0_popupItemsPanel" style="height: 64px;">
    <div class="opr-search2-popup-scroll-parent" tabindex="-1" ng-focus="oprSearch2Ctrl.onScrollParentFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)">
      <div class="opr-search2-popup-scroll-child" style="height: 64px;"></div>
    </div>
    <opr-search2-result class="table opr-search2-popup-items-table" style="width: 0px; top: 0px;">
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope focused" style="height: 32px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="ECommerce Servers_ Copy" search-item-id="ECommerce Servers_ Copy">
  <span class="opr-search2-term-highlight ng-binding"></span>ECommerce Servers_ Copy
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="SCOM_Ecommerce" search-item-id="SCOM_Ecommerce">
  <span class="opr-search2-term-highlight ng-binding"></span>SCOM_Ecommerce
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 32px; display: none;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="" search-item-id="">
  <span class="opr-search2-term-highlight ng-binding"></span>
</div>
</opr-search2-result-item>
    </opr-search2-result>
  </div>
  <div class="opr-search2-popup-status-panel ng-hide" id="oprSearch2_0_popupStatusPanel" title="" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.busyIconVisible">
    <div class="table opr-search2-popup-status-table">
      <div class="table-row">
        <div class="table-cell">
          <div class="opr-search2-popup-status-busy-icon loading-spinner"></div>
        </div>
        <div class="table-cell opr-search2-popup-status-text-cell ng-binding"></div>
      </div>
    </div>
  </div>
  <div class="opr-search2-popup-limit-panel ng-hide" id="oprSearch2_0_popupLimitPanel" title="More results available. Refine your search." ng-show="oprSearch2Ctrl.isMaxItemWarningVisible()">
    <div class="table opr-search2-popup-status-table">
      <div class="table-row">
        <div class="table-cell">
          <div class="opr-search2-popup-limit-icon">
            <i hpe-svg-icon="" class="qtm-icon qtm-icon-info qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" style="enable-background:new 0 0 16 16;" xml:space="preserve" focusable="false">
<g>
	<path d="M8,0C3.6,0,0,3.6,0,8s3.6,8,8,8s8-3.6,8-8S12.4,0,8,0z M8,15c-3.9,0-7-3.1-7-7s3.1-7,7-7s7,3.1,7,7S11.9,15,8,15z"></path>
	<circle cx="8" cy="5" r="1.5"></circle>
	<rect x="7" y="8" width="2" height="5"></rect>
</g>
</svg>
</i>
          </div>
        </div>
        <div class="table-cell opr-search2-popup-limit-text-cell ng-binding">More results available. Refine your search.</div>
      </div>
    </div>
  </div>
</div>
</opr-search2>
    </ng-transclude>
</div>
</opr-reveal-panel>
  </opr-horizontal-layout-item>

  <opr-horizontal-layout-item class="ng-scope opr-horizontal-layout-item expanded" style="width: auto; border-left: 4px solid transparent; border-right: 4px solid transparent;">
    <opr-reveal-panel ng-show="oprViewExplorerTreeCtrl.showCiSearch &amp;&amp; oprViewExplorerTreeCtrl.dataContext &amp;&amp; oprViewExplorerTreeCtrl.dataContext.root" label="Search" icon="qtm-icon-search--16" popup-width="283px" popup-height="auto" popup-horizontal-align="left" focus-on-reveal="opr-search2 input" reveal="oprViewExplorerTreeCtrl.revealCiSearch" class="" style=""><button class="btn btn-secondary btn-icon-only reveal-button" title="Search" ng-style="oprRevealPanelCtrl.revealButtonStyle" ng-click="oprRevealPanelCtrl.revealButtonClick()" id="" style="visibility: visible;">
  <!-- ngIf: oprRevealPanelCtrl.icon --><i ng-if="oprRevealPanelCtrl.icon" class="qtm-font-icon qtm-icon-default ng-scope qtm-icon-search--16" ng-class="[oprRevealPanelCtrl.icon]"></i><!-- end ngIf: oprRevealPanelCtrl.icon -->
  <!-- ngIf: !oprRevealPanelCtrl.icon -->
</button>
<div class="opr-reveal-panel-popup" ng-class="{'drop-shadow': oprRevealPanelCtrl.popupDropShadow === 'true'}" ng-style="oprRevealPanelCtrl.popupStyle" style="visibility: hidden; width: 283px; height: auto; right: 0px; top: 0px;">
  <ng-transclude>
      <opr-search2 class="ve-ci-search ng-untouched ng-valid ng-scope ng-isolate-scope opr-search2 ng-empty ng-dirty ng-valid-parse" mode="search" show-item-icons="true" item-source="oprViewExplorerTreeCtrl.dataContext.itemList" item-source-promise="oprViewExplorerTreeCtrl.dataContext.find" ng-model="oprViewExplorerTreeCtrl.ciSearchResultItem" has-focus="oprViewExplorerTreeCtrl.ciSearchHasFocus" placeholder="Search CIs in current view" loading-message="Loading more results..." ng-keydown="$event.stopPropagation()" item-height="22" min-visible-item-count="5" max-visible-item-count="20" highlight-placeholder="true"><div class="table opr-search2-panel search-mode" id="oprSearch2_1" ng-class="{'search-mode': oprSearch2Ctrl.mode === 'search', disabled: oprSearch2Ctrl.disabled}" selected-item-id="" title="Search CIs in current view" ng-mousedown="oprSearch2Ctrl.controlMouseUpDown($event)" ng-mouseup="oprSearch2Ctrl.controlMouseUpDown($event)">

  <div class="table-row">
    <div class="table-cell opr-search2-item-icon-cell ng-hide" ng-show="oprSearch2Ctrl.showItemIcons &amp;&amp; oprSearch2Ctrl.result.getSelectedItem().iconUrl">
      <div class="opr-search2-item-icon" ng-attr-style="background-image: url({{oprSearch2Ctrl.result.getSelectedItem().iconUrl}})">
      </div>&nbsp;
    </div>

    <div class="table-cell opr-search2-input-cell" style="width: 100%">
      <input tabindex="0" id="oprSearch2_1_input" class="opr-search2-input  highlight-placeholder" ng-class="{'highlight-placeholder': oprSearch2Ctrl.highlightPlaceholder === 'true'}" placeholder="Search CIs in current view" autocomplete="off" aria-autocomplete="none" ng-disabled="oprSearch2Ctrl.disabled" ng-focus="oprSearch2Ctrl.onControlFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)" ng-keydown="oprSearch2Ctrl.inputKeyDown($event)" ng-mouseup="oprSearch2Ctrl.inputMouseUp($event)" ng-mousedown="oprSearch2Ctrl.inputMouseDown($event)" ng-model="oprSearch2Ctrl.searchTerm" opr-select-on-focus="">
    </div>

    <div class="table-cell opr-search2-result-count-cell ng-binding ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.result.getSelectedItem()" id="oprSearch2_1resultCountCell" data-selected-item-index-and-total-items="0 of 107">
         0 of 107
    </div>

    <div class="table-cell opr-search2-button-cell prev btn-toolbar no-padding ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.result.getSelectedItem()">
      <button class="prev btn btn-secondary" ng-focus="oprSearch2Ctrl.onControlFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)" ng-click="oprSearch2Ctrl.result.setSelectedItemIndexRelative(-1)" title="Move Up">
        <i hpe-svg-icon="" class="opr-search2-search-icon qtm-icon-up--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<polygon points="2.6,7.6 3.4,8.4 8,3.7 8,15 9,15 9,3.7 13.6,8.4 14.4,7.6 8.5,1.8 "></polygon>
</svg>
</i>
      </button>
    </div>

    <div class="table-cell opr-search2-button-cell next btn-toolbar no-padding ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.result.getSelectedItem()">
      <button class="next btn btn-secondary" ng-focus="oprSearch2Ctrl.onControlFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)" ng-click="oprSearch2Ctrl.result.setSelectedItemIndexRelative(1)" title="Move Down">
        <i hpe-svg-icon="" class="opr-search2-search-icon qtm-icon-down--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<polygon points="14.4,8.4 13.6,7.6 9,12.3 9,1 8,1 8,12.3 3.4,7.6 2.6,8.4 8.5,14.2 "></polygon>
</svg>
</i>
      </button>
    </div>

    <div class="table-cell opr-search2-dropdown-icon-cell ng-hide" ng-show="oprSearch2Ctrl.isInDropdownMode() &amp;&amp; oprSearch2Ctrl.popupVisible" ng-click="oprSearch2Ctrl.dropdownIconClick('close')">
      <div class="opr-search2-dropdown-icon-container open">
        <!--<div class="opr-search2-dropdown-icon">.</div>-->
        <div class="caret"></div>
      </div>
    </div>

    <div class="table-cell opr-search2-dropdown-icon-cell ng-hide" ng-show="oprSearch2Ctrl.isInDropdownMode() &amp;&amp; !oprSearch2Ctrl.popupVisible" ng-click="oprSearch2Ctrl.dropdownIconClick('show')">
      <div class="opr-search2-dropdown-icon-container">
        <div class="caret"></div>
      </div>
    </div>

    <div class="table-cell opr-search2-search-icon-cell" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; (!oprSearch2Ctrl.searchTerm || (oprSearch2Ctrl.searchTerm.length === 0))">
      <div class="opr-search2-search-icon-container" ng-click="oprSearch2Ctrl.searchIconClick()" title="Search">
        <i hpe-svg-icon="" class="opr-search2-search-icon qtm-icon-search--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<path d="M15.354,14.646L10.577,9.87C11.463,8.825,12,7.475,12,6c0-3.309-2.691-6-6-6S0,2.691,0,6s2.691,6,6,6
	c1.475,0,2.825-0.537,3.87-1.423l4.776,4.776L15.354,14.646z M6,11c-2.757,0-5-2.243-5-5s2.243-5,5-5s5,2.243,5,5S8.757,11,6,11z"></path>
</svg>
</i>
      </div>
    </div>

    <div class="table-cell opr-search2-clear-icon-cell ng-hide" ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.searchTerm &amp;&amp; (oprSearch2Ctrl.searchTerm.length > 0)">
      <div class="opr-search2-clear-icon-container" ng-click="oprSearch2Ctrl.clearIconClick()" title="Clear">
        <i hpe-svg-icon="" class="opr-search2-clear-icon qtm-icon-search-cancel--16 qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" enable-background="new 0 0 16 16" xml:space="preserve" focusable="false">
<path d="M8.7,8l5.6-5.6c0.2-0.2,0.2-0.5,0-0.7s-0.5-0.2-0.7,0L8,7.3L2.4,1.6c-0.2-0.2-0.5-0.2-0.7,0s-0.2,0.5,0,0.7L7.3,8l-5.6,5.6
	c-0.2,0.2-0.2,0.5,0,0.7c0.1,0.1,0.2,0.1,0.4,0.1s0.3,0,0.4-0.1L8,8.7l5.6,5.6c0.1,0.1,0.2,0.1,0.4,0.1s0.3,0,0.4-0.1
	c0.2-0.2,0.2-0.5,0-0.7L8.7,8z"></path>
</svg>
</i>
      </div>
    </div>

    <!-- ngIf: oprSearch2Ctrl.buttonActions && oprSearch2Ctrl.buttonActions.length > 0 -->

  </div>
</div>

<div class="opr-search2-popup" style="display: none;">
  <div class="opr-search2-popup-items-panel" id="oprSearch2_1_popupItemsPanel">
    <div class="opr-search2-popup-scroll-parent" tabindex="-1" ng-focus="oprSearch2Ctrl.onScrollParentFocus($event)" ng-blur="oprSearch2Ctrl.onControlBlur($event)">
      <div class="opr-search2-popup-scroll-child" style="height: 2354px;"></div>
    </div>
    <opr-search2-result class="table opr-search2-popup-items-table" style="width: 0px; top: 0px;">
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-b01" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;475f9132c6acc5a5ab79d52e41de2d5a">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-b01
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-b02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;43f6aa7e0a83c6449debecdad657a90d">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-b02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-dc01" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;45063bcd784f18738942c45bd74dd975">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-dc01
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-dc02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;410899a903a666bc9bd605adcac1327a">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-dc02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-i01" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;488415c54bf64a619de0e0275cb987e5">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-i01
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-i02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;40ed642bbd02b762a2619a909546bf95">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-i02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-r01" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;409a19b936cbd0a79d8e55dacdda7944">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-r01
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-w01" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;45a6510d4c477af39e421b5a28464e0a">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-w01
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="a2w-epg-w02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;44bf160167d7d6f9bce1f581ccb73151">
  <span class="opr-search2-term-highlight ng-binding"></span>a2w-epg-w02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as00035azaen00" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4a1eed3e1856b54e846dc0fa06ca6e46">
  <span class="opr-search2-term-highlight ng-binding"></span>as00035azaen00
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as1009dxbdb05" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4fc36b64ccf2cdbbba83e2818d979c7d">
  <span class="opr-search2-term-highlight ng-binding"></span>as1009dxbdb05
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as1010dxbdb05" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4326843507bd7c02b7dd4637bb7a45ce">
  <span class="opr-search2-term-highlight ng-binding"></span>as1010dxbdb05
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as1011dxbdb05" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;429ae6e87d0eda589e76ece061f8a875">
  <span class="opr-search2-term-highlight ng-binding"></span>as1011dxbdb05
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as1012dxbdb05" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;47a88f32bcd06edcb8d695a1c5e278f7">
  <span class="opr-search2-term-highlight ng-binding"></span>as1012dxbdb05
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as10215aufal02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4014367580eb5f008fa8dc9707410a62">
  <span class="opr-search2-term-highlight ng-binding"></span>as10215aufal02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as10898aufal02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;41122d010c43c75aac86e30d1aa6a895">
  <span class="opr-search2-term-highlight ng-binding"></span>as10898aufal02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as10899aufal02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4a90a9dea668dcb184f63edd796982e4">
  <span class="opr-search2-term-highlight ng-binding"></span>as10899aufal02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as21563dxbdb05" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;470c4910175e1b16a4e038325d71fb5d">
  <span class="opr-search2-term-highlight ng-binding"></span>as21563dxbdb05
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as21564aufal02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4c996b7f275140b7be3e5ba9d5d65643">
  <span class="opr-search2-term-highlight ng-binding"></span>as21564aufal02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as21598aufal02" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;4662038e2389b7a2acae85f4d908d0c7">
  <span class="opr-search2-term-highlight ng-binding"></span>as21598aufal02
</div>
</opr-search2-result-item>
    
      <opr-search2-result-item class="table-row opr-search2-popup-items-row ng-scope" style="height: 22px;"><div class="table-cell opr-search2-popup-items-column-padding"></div>
<!-- ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] --><div class="table-cell opr-search2-popup-items-column-icon ng-scope" ng-if="oprSearch2Ctrl.showItemIcons &amp;&amp; item[oprSearch2Ctrl.itemIconField]" style=""><div class="opr-search2-item-icon" ng-attr-style="background-image: url({{item[oprSearch2Ctrl.itemIconField]}})" style="background-image: url(/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg)"></div>&nbsp;</div><!-- end ngIf: oprSearch2Ctrl.showItemIcons && item[oprSearch2Ctrl.itemIconField] -->
<!-- ngIf: oprSearch2Ctrl.showItemHpeIcons && item[oprSearch2Ctrl.itemHpeIconField] -->
<div class="table-cell opr-search2-popup-items-column-label ng-binding" title="as21599dxbdb05" search-item-id="1;;4d7ded18276957419ca7f2747e4e2041;;440b2faac15e62a3bae18e11498c895b">
  <span class="opr-search2-term-highlight ng-binding"></span>as21599dxbdb05
</div>
</opr-search2-result-item>
    </opr-search2-result>
  </div>
  <div class="opr-search2-popup-status-panel ng-hide" id="oprSearch2_1_popupStatusPanel" title="Loading more results..." ng-show="oprSearch2Ctrl.isInSearchMode() &amp;&amp; oprSearch2Ctrl.busyIconVisible">
    <div class="table opr-search2-popup-status-table">
      <div class="table-row">
        <div class="table-cell">
          <div class="opr-search2-popup-status-busy-icon loading-spinner"></div>
        </div>
        <div class="table-cell opr-search2-popup-status-text-cell ng-binding">Loading more results...</div>
      </div>
    </div>
  </div>
  <div class="opr-search2-popup-limit-panel ng-hide" id="oprSearch2_1_popupLimitPanel" title="More results available. Refine your search." ng-show="oprSearch2Ctrl.isMaxItemWarningVisible()">
    <div class="table opr-search2-popup-status-table">
      <div class="table-row">
        <div class="table-cell">
          <div class="opr-search2-popup-limit-icon">
            <i hpe-svg-icon="" class="qtm-icon qtm-icon-info qtm-icon-blurry-fix" style="background-image: none; pointer-events: none;"><!--?xml version="1.0" encoding="utf-8"?-->
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 16 16" style="enable-background:new 0 0 16 16;" xml:space="preserve" focusable="false">
<g>
	<path d="M8,0C3.6,0,0,3.6,0,8s3.6,8,8,8s8-3.6,8-8S12.4,0,8,0z M8,15c-3.9,0-7-3.1-7-7s3.1-7,7-7s7,3.1,7,7S11.9,15,8,15z"></path>
	<circle cx="8" cy="5" r="1.5"></circle>
	<rect x="7" y="8" width="2" height="5"></rect>
</g>
</svg>
</i>
          </div>
        </div>
        <div class="table-cell opr-search2-popup-limit-text-cell ng-binding">More results available. Refine your search.</div>
      </div>
    </div>
  </div>
</div>
</opr-search2>
    </ng-transclude>
</div>
</opr-reveal-panel>
  </opr-horizontal-layout-item>

  <opr-horizontal-layout-item fill="true" class="ng-scope opr-horizontal-layout-item expanded" style="width: 100%;">&nbsp;</opr-horizontal-layout-item>


    <opr-horizontal-layout class="ng-scope opr-horizontal-layout"><div class="opr-horizontal-layout-container">
        <opr-horizontal-layout-item fill="true" class="ng-scope opr-horizontal-layout-item expanded" style="width: 100%;"></opr-horizontal-layout-item>
        <opr-horizontal-layout-item class="ng-scope opr-horizontal-layout-item expanded" style="width: auto;">
            <!-- ngIf: !oprViewExplorerCtrl.hideOptionsButton --><button type="button" class="btn btn-icon btn-icon-only ng-scope" ng-if="!oprViewExplorerCtrl.hideOptionsButton" ng-click="oprViewExplorerCtrl.showOptions()" title="Options">
                <i class="qtm-font-icon qtm-icon-menu" aria-hidden="true"></i>
            </button><!-- end ngIf: !oprViewExplorerCtrl.hideOptionsButton -->
        </opr-horizontal-layout-item>
    </div></opr-horizontal-layout>
</div></opr-horizontal-layout>
  <div class="ve-tree-container" cg-busy="oprViewExplorerTreeCtrl.loadingPromises" style="position: relative;">
  <opr-tree-view style="position: absolute; left: 0; top: 0; right: 0; bottom: 0" opr-tree-view-keyboard-navigation="" opr-view-explorer-tree-lazy-loading="" opr-tree-view-expand-animation="" animated-element-selector=".ve-tree-item-row" animated-expander-expanded-selector=".ve-tree-item-expander-expanded" animated-expander-collapsed-selector=".ve-tree-item-expander-collapsed" multi-selection="oprViewExplorerTreeCtrl.multiSelection" invert-preserve-selection="oprViewExplorerTreeCtrl.invertPreserveSelection" integral-scrolling="false" item-height="32" api="oprViewExplorerTreeCtrl.treeViewApi" on-selection-changed="oprViewExplorerTreeCtrl.onSelectionChanged" class="ng-scope"><div class="opr-tree-view-scroll-parent ng-scope"><div class="opr-tree-view-scroll-child" style="position: absolute; left: 0px; top: 0px; right: 0px; height: 3424px;"></div></div><div class="opr-tree-view-control-area" tabindex="0" unselectable="on" style="position: absolute; inset: 0px 15px 0px 0px; overflow: hidden; user-select: none; outline: none;">
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 1024px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/unix/unix_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="au10752 [Unix]">au10752</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 992px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/unix/unix_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="au10683 [Unix]">au10683</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 960px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/unix/unix_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="au10682 [Unix]">au10682</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 928px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/unix/unix_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="au10546 [Unix]">au10546</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 896px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/unix/unix_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="au10545 [Unix]">au10545</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 864px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/unix/unix_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="au10544 [Unix]">au10544</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 832px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21759dxbdb05 [Windows]">as21759dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 800px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21758dxbdb05 [Windows]">as21758dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 768px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21757aufal02 [Windows]">as21757aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 736px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21756aufal02 [Windows]">as21756aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 704px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21599dxbdb05 [Windows]">as21599dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 672px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21598aufal02 [Windows]">as21598aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 640px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21564aufal02 [Windows]">as21564aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 608px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as21563dxbdb05 [Windows]">as21563dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 576px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as10899aufal02 [Windows]">as10899aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 544px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as10898aufal02 [Windows]">as10898aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 512px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as10215aufal02 [Windows]">as10215aufal02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 480px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as1012dxbdb05 [Windows]">as1012dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 448px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as1011dxbdb05 [Windows]">as1011dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 416px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as1010dxbdb05 [Windows]">as1010dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 384px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as1009dxbdb05 [Windows]">as1009dxbdb05</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 352px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="as00035azaen00 [Windows]">as00035azaen00</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 320px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-w02 [Windows]">a2w-epg-w02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 288px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-w01 [Windows]">a2w-epg-w01</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 256px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-r01 [Windows]">a2w-epg-r01</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 224px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-i02 [Windows]">a2w-epg-i02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 192px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-i01 [Windows]">a2w-epg-i01</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 160px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-dc02 [Windows]">a2w-epg-dc02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 128px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-dc01 [Windows]">a2w-epg-dc01</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 96px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-b02 [Windows]">a2w-epg-b02</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 64px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 24px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/nt/nt_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="a2w-epg-b01 [Windows]">a2w-epg-b01</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 32px;"><div class="ve-tree-item-row" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: 4px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: block;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/logical_group/logical_group_32.svg&quot;);"></div>
    <div class="ve-tree-item-label" title="ecommerce.support Servers [CiCollection]">ecommerce.support Servers</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  
    <opr-view-explorer-tree-item item-indentation="20" class="ng-scope ve-tree-item" style="display: block; height: 32px; line-height: 32px; top: 0px;"><div class="ve-tree-item-row selected focused" ng-click="oprViewExplorerTreeItemCtrl.itemClick($event)" ng-dblclick="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="height: 32px;">
  <div class="ve-tree-item-checkmark-container"><div class="ve-tree-item-checkmark"></div></div>
  <div class="ve-tree-item-container" style="left: -16px;">
    <div class="ve-tree-item-expander ve-tree-item-expander-expanded" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-down qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-expander ve-tree-item-expander-collapsed" ng-click="oprViewExplorerTreeItemCtrl.toggleItemExpanded()" style="display: none;">
      <i class="qtm-font-icon qtm-icon-caret-right qtm-icon-small-10" aria-hidden="true"></i>
    </div>
    <div class="ve-tree-item-icon invert-icon-in-dark-theme" style="background-image: url(&quot;/topaz/static/ODB/images/citypes/icons/view1/view1_16.png&quot;);"></div>
    <div class="ve-tree-item-label" title="ECommerce Servers_ Copy - Root">ECommerce Servers_ Copy</div>
    <div class="btn-toolbar">
      <div class="btn-group">
        <!-- ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="collapse" title="Collapse all" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope" style="">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index --><!-- ngIf: !action.isGrouped --><opr-button ng-repeat="action in oprViewExplorerTreeCtrl.itemActions track by $index" ng-if="!action.isGrouped" icon="context-menu" title="Actions" ng-show="!action.checkAvailabilityFunction || action.checkAvailabilityFunction(item, oprViewExplorerTreeItemCtrl)" is-disabled="action.checkDisabledFunction &amp;&amp; action.checkDisabledFunction(item, oprViewExplorerTreeItemCtrl)" ng-click="action.actionFunction(item, oprViewExplorerTreeItemCtrl, $event)" variant="primary" class="ng-scope ng-hide">
        </opr-button><!-- end ngIf: !action.isGrouped --><!-- end ngRepeat: action in oprViewExplorerTreeCtrl.itemActions track by $index -->
      </div>
    </div>
  </div>
</div>
</opr-view-explorer-tree-item>
  </div></opr-tree-view>

  <!-- ngIf: !oprViewExplorerTreeCtrl.viewSelectorSelectedView || oprViewExplorerTreeCtrl.dataContext.errorMessage -->

<div class="cg-busy cg-busy-backdrop cg-busy-backdrop-animation ng-scope ng-hide" ng-show="$cgBusyIsActive()" style=""></div><div class="cg-busy cg-busy-animation ng-scope ng-hide" ng-show="$cgBusyIsActive()" style=""><div style="position: absolute; inset: 0px;">
  <div class="loading_spinner">
</div></div></div></div>
</opr-view-explorer-tree>
