Section 13 : SASS et Bootstrap
===

## Information
- Title:  `SASS et Bootstrap`
- Authors:  `Etienne KOA`



## Presentation SASSS

+ Utilisez nos fichiers Sass sources pour profiter des variables, des cartes, des mixins et des fonctions pour vous aider à construire plus rapidement et à personnaliser votre projet.

## Commandes

```
npm init

npm install bootstrap@next

npm install -g sass

npm bin -g

set PATH=%PATH%;C:\Users\etixicode\AppData\Roaming\npm

C:\Bootstrap5_La_Formation_Ultime>sass --version
1.71.1 compiled with dart2js 3.3.0

C:\Bootstrap5_La_Formation_Ultime>cd Section13_SAAS_Et_Bootstrap

C:\Bootstrap5_La_Formation_Ultime\Section13_SAAS_Et_Bootstrap>sass --watch design/default.scss design/default.css
[2024-03-13 18:41] Compiled design\default.scss to design\default.css.
Sass is watching for changes. Press Ctrl-C to stop

sass --watch design/default.scss design/default.css -s compressed 
```


## Directory Hierarchy
```
|—— node_modules
|    |—— .package-lock.json
|    |—— @popperjs
|        |—— core
|            |—— dist
|                |—— cjs
|                    |—— enums.js
|                    |—— enums.js.flow
|                    |—— enums.js.map
|                    |—— popper-base.js
|                    |—— popper-base.js.flow
|                    |—— popper-base.js.map
|                    |—— popper-lite.js
|                    |—— popper-lite.js.flow
|                    |—— popper-lite.js.map
|                    |—— popper.js
|                    |—— popper.js.flow
|                    |—— popper.js.map
|                |—— esm
|                    |—— createPopper.js
|                    |—— dom-utils
|                        |—— contains.js
|                        |—— getBoundingClientRect.js
|                        |—— getClippingRect.js
|                        |—— getCompositeRect.js
|                        |—— getComputedStyle.js
|                        |—— getDocumentElement.js
|                        |—— getDocumentRect.js
|                        |—— getHTMLElementScroll.js
|                        |—— getLayoutRect.js
|                        |—— getNodeName.js
|                        |—— getNodeScroll.js
|                        |—— getOffsetParent.js
|                        |—— getParentNode.js
|                        |—— getScrollParent.js
|                        |—— getViewportRect.js
|                        |—— getWindow.js
|                        |—— getWindowScroll.js
|                        |—— getWindowScrollBarX.js
|                        |—— instanceOf.js
|                        |—— isLayoutViewport.js
|                        |—— isScrollParent.js
|                        |—— isTableElement.js
|                        |—— listScrollParents.js
|                    |—— enums.js
|                    |—— index.js
|                    |—— modifiers
|                        |—— applyStyles.js
|                        |—— arrow.js
|                        |—— computeStyles.js
|                        |—— eventListeners.js
|                        |—— flip.js
|                        |—— hide.js
|                        |—— index.js
|                        |—— offset.js
|                        |—— popperOffsets.js
|                        |—— preventOverflow.js
|                    |—— popper-base.js
|                    |—— popper-lite.js
|                    |—— popper.js
|                    |—— types.js
|                    |—— utils
|                        |—— computeAutoPlacement.js
|                        |—— computeOffsets.js
|                        |—— debounce.js
|                        |—— detectOverflow.js
|                        |—— expandToHashMap.js
|                        |—— getAltAxis.js
|                        |—— getAltLen.js
|                        |—— getBasePlacement.js
|                        |—— getFreshSideObject.js
|                        |—— getMainAxisFromPlacement.js
|                        |—— getOppositePlacement.js
|                        |—— getOppositeVariationPlacement.js
|                        |—— getVariation.js
|                        |—— math.js
|                        |—— mergeByName.js
|                        |—— mergePaddingObject.js
|                        |—— orderModifiers.js
|                        |—— rectToClientRect.js
|                        |—— uniqueBy.js
|                        |—— userAgent.js
|                        |—— within.js
|                |—— umd
|                    |—— enums.js
|                    |—— enums.js.map
|                    |—— enums.min.js
|                    |—— enums.min.js.flow
|                    |—— enums.min.js.map
|                    |—— popper-base.js
|                    |—— popper-base.js.map
|                    |—— popper-base.min.js
|                    |—— popper-base.min.js.flow
|                    |—— popper-base.min.js.map
|                    |—— popper-lite.js
|                    |—— popper-lite.js.map
|                    |—— popper-lite.min.js
|                    |—— popper-lite.min.js.flow
|                    |—— popper-lite.min.js.map
|                    |—— popper.js
|                    |—— popper.js.map
|                    |—— popper.min.js
|                    |—— popper.min.js.flow
|                    |—— popper.min.js.map
|            |—— index.d.ts
|            |—— lib
|                |—— createPopper.d.ts
|                |—— createPopper.js
|                |—— createPopper.js.flow
|                |—— dom-utils
|                    |—— contains.d.ts
|                    |—— contains.js
|                    |—— contains.js.flow
|                    |—— getBoundingClientRect.d.ts
|                    |—— getBoundingClientRect.js
|                    |—— getBoundingClientRect.js.flow
|                    |—— getClippingRect.d.ts
|                    |—— getClippingRect.js
|                    |—— getClippingRect.js.flow
|                    |—— getCompositeRect.d.ts
|                    |—— getCompositeRect.js
|                    |—— getCompositeRect.js.flow
|                    |—— getComputedStyle.d.ts
|                    |—— getComputedStyle.js
|                    |—— getComputedStyle.js.flow
|                    |—— getDocumentElement.d.ts
|                    |—— getDocumentElement.js
|                    |—— getDocumentElement.js.flow
|                    |—— getDocumentRect.d.ts
|                    |—— getDocumentRect.js
|                    |—— getDocumentRect.js.flow
|                    |—— getHTMLElementScroll.d.ts
|                    |—— getHTMLElementScroll.js
|                    |—— getHTMLElementScroll.js.flow
|                    |—— getLayoutRect.d.ts
|                    |—— getLayoutRect.js
|                    |—— getLayoutRect.js.flow
|                    |—— getNodeName.d.ts
|                    |—— getNodeName.js
|                    |—— getNodeName.js.flow
|                    |—— getNodeScroll.d.ts
|                    |—— getNodeScroll.js
|                    |—— getNodeScroll.js.flow
|                    |—— getOffsetParent.d.ts
|                    |—— getOffsetParent.js
|                    |—— getOffsetParent.js.flow
|                    |—— getParentNode.d.ts
|                    |—— getParentNode.js
|                    |—— getParentNode.js.flow
|                    |—— getScrollParent.d.ts
|                    |—— getScrollParent.js
|                    |—— getScrollParent.js.flow
|                    |—— getViewportRect.d.ts
|                    |—— getViewportRect.js
|                    |—— getViewportRect.js.flow
|                    |—— getWindow.d.ts
|                    |—— getWindow.js
|                    |—— getWindow.js.flow
|                    |—— getWindowScroll.d.ts
|                    |—— getWindowScroll.js
|                    |—— getWindowScroll.js.flow
|                    |—— getWindowScrollBarX.d.ts
|                    |—— getWindowScrollBarX.js
|                    |—— getWindowScrollBarX.js.flow
|                    |—— instanceOf.d.ts
|                    |—— instanceOf.js
|                    |—— instanceOf.js.flow
|                    |—— isLayoutViewport.d.ts
|                    |—— isLayoutViewport.js
|                    |—— isLayoutViewport.js.flow
|                    |—— isScrollParent.d.ts
|                    |—— isScrollParent.js
|                    |—— isScrollParent.js.flow
|                    |—— isTableElement.d.ts
|                    |—— isTableElement.js
|                    |—— isTableElement.js.flow
|                    |—— listScrollParents.d.ts
|                    |—— listScrollParents.js
|                    |—— listScrollParents.js.flow
|                |—— enums.d.ts
|                |—— enums.js
|                |—— enums.js.flow
|                |—— index.d.ts
|                |—— index.js
|                |—— index.js.flow
|                |—— modifiers
|                    |—— applyStyles.d.ts
|                    |—— applyStyles.js
|                    |—— applyStyles.js.flow
|                    |—— arrow.d.ts
|                    |—— arrow.js
|                    |—— arrow.js.flow
|                    |—— computeStyles.d.ts
|                    |—— computeStyles.js
|                    |—— computeStyles.js.flow
|                    |—— eventListeners.d.ts
|                    |—— eventListeners.js
|                    |—— eventListeners.js.flow
|                    |—— flip.d.ts
|                    |—— flip.js
|                    |—— flip.js.flow
|                    |—— hide.d.ts
|                    |—— hide.js
|                    |—— hide.js.flow
|                    |—— index.d.ts
|                    |—— index.js
|                    |—— index.js.flow
|                    |—— offset.d.ts
|                    |—— offset.js
|                    |—— offset.js.flow
|                    |—— popperOffsets.d.ts
|                    |—— popperOffsets.js
|                    |—— popperOffsets.js.flow
|                    |—— preventOverflow.d.ts
|                    |—— preventOverflow.js
|                    |—— preventOverflow.js.flow
|                |—— popper-base.d.ts
|                |—— popper-base.js
|                |—— popper-base.js.flow
|                |—— popper-lite.d.ts
|                |—— popper-lite.js
|                |—— popper-lite.js.flow
|                |—— popper.d.ts
|                |—— popper.js
|                |—— popper.js.flow
|                |—— types.d.ts
|                |—— types.js
|                |—— types.js.flow
|                |—— utils
|                    |—— computeAutoPlacement.d.ts
|                    |—— computeAutoPlacement.js
|                    |—— computeAutoPlacement.js.flow
|                    |—— computeOffsets.d.ts
|                    |—— computeOffsets.js
|                    |—— computeOffsets.js.flow
|                    |—— debounce.d.ts
|                    |—— debounce.js
|                    |—— debounce.js.flow
|                    |—— detectOverflow.d.ts
|                    |—— detectOverflow.js
|                    |—— detectOverflow.js.flow
|                    |—— expandToHashMap.d.ts
|                    |—— expandToHashMap.js
|                    |—— expandToHashMap.js.flow
|                    |—— getAltAxis.d.ts
|                    |—— getAltAxis.js
|                    |—— getAltAxis.js.flow
|                    |—— getAltLen.d.ts
|                    |—— getAltLen.js
|                    |—— getAltLen.js.flow
|                    |—— getBasePlacement.d.ts
|                    |—— getBasePlacement.js
|                    |—— getBasePlacement.js.flow
|                    |—— getFreshSideObject.d.ts
|                    |—— getFreshSideObject.js
|                    |—— getFreshSideObject.js.flow
|                    |—— getMainAxisFromPlacement.d.ts
|                    |—— getMainAxisFromPlacement.js
|                    |—— getMainAxisFromPlacement.js.flow
|                    |—— getOppositePlacement.d.ts
|                    |—— getOppositePlacement.js
|                    |—— getOppositePlacement.js.flow
|                    |—— getOppositeVariationPlacement.d.ts
|                    |—— getOppositeVariationPlacement.js
|                    |—— getOppositeVariationPlacement.js.flow
|                    |—— getVariation.d.ts
|                    |—— getVariation.js
|                    |—— getVariation.js.flow
|                    |—— math.d.ts
|                    |—— math.js
|                    |—— math.js.flow
|                    |—— mergeByName.d.ts
|                    |—— mergeByName.js
|                    |—— mergeByName.js.flow
|                    |—— mergePaddingObject.d.ts
|                    |—— mergePaddingObject.js
|                    |—— mergePaddingObject.js.flow
|                    |—— orderModifiers.d.ts
|                    |—— orderModifiers.js
|                    |—— orderModifiers.js.flow
|                    |—— rectToClientRect.d.ts
|                    |—— rectToClientRect.js
|                    |—— rectToClientRect.js.flow
|                    |—— uniqueBy.d.ts
|                    |—— uniqueBy.js
|                    |—— uniqueBy.js.flow
|                    |—— userAgent.d.ts
|                    |—— userAgent.js
|                    |—— userAgent.js.flow
|                    |—— within.d.ts
|                    |—— within.js
|                    |—— within.js.flow
|            |—— LICENSE.md
|            |—— package.json
|            |—— README.md
|    |—— bootstrap
|        |—— dist
|            |—— css
|                |—— bootstrap-grid.css
|                |—— bootstrap-grid.css.map
|                |—— bootstrap-grid.min.css
|                |—— bootstrap-grid.min.css.map
|                |—— bootstrap-grid.rtl.css
|                |—— bootstrap-grid.rtl.css.map
|                |—— bootstrap-grid.rtl.min.css
|                |—— bootstrap-grid.rtl.min.css.map
|                |—— bootstrap-reboot.css
|                |—— bootstrap-reboot.css.map
|                |—— bootstrap-reboot.min.css
|                |—— bootstrap-reboot.min.css.map
|                |—— bootstrap-reboot.rtl.css
|                |—— bootstrap-reboot.rtl.css.map
|                |—— bootstrap-reboot.rtl.min.css
|                |—— bootstrap-reboot.rtl.min.css.map
|                |—— bootstrap-utilities.css
|                |—— bootstrap-utilities.css.map
|                |—— bootstrap-utilities.min.css
|                |—— bootstrap-utilities.min.css.map
|                |—— bootstrap-utilities.rtl.css
|                |—— bootstrap-utilities.rtl.css.map
|                |—— bootstrap-utilities.rtl.min.css
|                |—— bootstrap-utilities.rtl.min.css.map
|                |—— bootstrap.css
|                |—— bootstrap.css.map
|                |—— bootstrap.min.css
|                |—— bootstrap.min.css.map
|                |—— bootstrap.rtl.css
|                |—— bootstrap.rtl.css.map
|                |—— bootstrap.rtl.min.css
|                |—— bootstrap.rtl.min.css.map
|            |—— js
|                |—— bootstrap.bundle.js
|                |—— bootstrap.bundle.js.map
|                |—— bootstrap.bundle.min.js
|                |—— bootstrap.bundle.min.js.map
|                |—— bootstrap.esm.js
|                |—— bootstrap.esm.js.map
|                |—— bootstrap.esm.min.js
|                |—— bootstrap.esm.min.js.map
|                |—— bootstrap.js
|                |—— bootstrap.js.map
|                |—— bootstrap.min.js
|                |—— bootstrap.min.js.map
|        |—— js
|            |—— dist
|                |—— alert.js
|                |—— alert.js.map
|                |—— base-component.js
|                |—— base-component.js.map
|                |—— button.js
|                |—— button.js.map
|                |—— carousel.js
|                |—— carousel.js.map
|                |—— collapse.js
|                |—— collapse.js.map
|                |—— dom
|                    |—— data.js
|                    |—— data.js.map
|                    |—— event-handler.js
|                    |—— event-handler.js.map
|                    |—— manipulator.js
|                    |—— manipulator.js.map
|                    |—— selector-engine.js
|                    |—— selector-engine.js.map
|                |—— dropdown.js
|                |—— dropdown.js.map
|                |—— modal.js
|                |—— modal.js.map
|                |—— offcanvas.js
|                |—— offcanvas.js.map
|                |—— popover.js
|                |—— popover.js.map
|                |—— scrollspy.js
|                |—— scrollspy.js.map
|                |—— tab.js
|                |—— tab.js.map
|                |—— toast.js
|                |—— toast.js.map
|                |—— tooltip.js
|                |—— tooltip.js.map
|                |—— util
|                    |—— backdrop.js
|                    |—— backdrop.js.map
|                    |—— component-functions.js
|                    |—— component-functions.js.map
|                    |—— config.js
|                    |—— config.js.map
|                    |—— focustrap.js
|                    |—— focustrap.js.map
|                    |—— index.js
|                    |—— index.js.map
|                    |—— sanitizer.js
|                    |—— sanitizer.js.map
|                    |—— scrollbar.js
|                    |—— scrollbar.js.map
|                    |—— swipe.js
|                    |—— swipe.js.map
|                    |—— template-factory.js
|                    |—— template-factory.js.map
|            |—— index.esm.js
|            |—— index.umd.js
|            |—— src
|                |—— alert.js
|                |—— base-component.js
|                |—— button.js
|                |—— carousel.js
|                |—— collapse.js
|                |—— dom
|                    |—— data.js
|                    |—— event-handler.js
|                    |—— manipulator.js
|                    |—— selector-engine.js
|                |—— dropdown.js
|                |—— modal.js
|                |—— offcanvas.js
|                |—— popover.js
|                |—— scrollspy.js
|                |—— tab.js
|                |—— toast.js
|                |—— tooltip.js
|                |—— util
|                    |—— backdrop.js
|                    |—— component-functions.js
|                    |—— config.js
|                    |—— focustrap.js
|                    |—— index.js
|                    |—— sanitizer.js
|                    |—— scrollbar.js
|                    |—— swipe.js
|                    |—— template-factory.js
|        |—— LICENSE
|        |—— package.json
|        |—— README.md
|        |—— scss
|            |—— bootstrap-grid.scss
|            |—— bootstrap-reboot.scss
|            |—— bootstrap-utilities.scss
|            |—— bootstrap.scss
|            |—— forms
|                |—— _floating-labels.scss
|                |—— _form-check.scss
|                |—— _form-control.scss
|                |—— _form-range.scss
|                |—— _form-select.scss
|                |—— _form-text.scss
|                |—— _input-group.scss
|                |—— _labels.scss
|                |—— _validation.scss
|            |—— helpers
|                |—— _clearfix.scss
|                |—— _color-bg.scss
|                |—— _colored-links.scss
|                |—— _focus-ring.scss
|                |—— _icon-link.scss
|                |—— _position.scss
|                |—— _ratio.scss
|                |—— _stacks.scss
|                |—— _stretched-link.scss
|                |—— _text-truncation.scss
|                |—— _visually-hidden.scss
|                |—— _vr.scss
|            |—— mixins
|                |—— _alert.scss
|                |—— _backdrop.scss
|                |—— _banner.scss
|                |—— _border-radius.scss
|                |—— _box-shadow.scss
|                |—— _breakpoints.scss
|                |—— _buttons.scss
|                |—— _caret.scss
|                |—— _clearfix.scss
|                |—— _color-mode.scss
|                |—— _color-scheme.scss
|                |—— _container.scss
|                |—— _deprecate.scss
|                |—— _forms.scss
|                |—— _gradients.scss
|                |—— _grid.scss
|                |—— _image.scss
|                |—— _list-group.scss
|                |—— _lists.scss
|                |—— _pagination.scss
|                |—— _reset-text.scss
|                |—— _resize.scss
|                |—— _table-variants.scss
|                |—— _text-truncate.scss
|                |—— _transition.scss
|                |—— _utilities.scss
|                |—— _visually-hidden.scss
|            |—— utilities
|                |—— _api.scss
|            |—— vendor
|                |—— _rfs.scss
|            |—— _accordion.scss
|            |—— _alert.scss
|            |—— _badge.scss
|            |—— _breadcrumb.scss
|            |—— _button-group.scss
|            |—— _buttons.scss
|            |—— _card.scss
|            |—— _carousel.scss
|            |—— _close.scss
|            |—— _containers.scss
|            |—— _dropdown.scss
|            |—— _forms.scss
|            |—— _functions.scss
|            |—— _grid.scss
|            |—— _helpers.scss
|            |—— _images.scss
|            |—— _list-group.scss
|            |—— _maps.scss
|            |—— _mixins.scss
|            |—— _modal.scss
|            |—— _nav.scss
|            |—— _navbar.scss
|            |—— _offcanvas.scss
|            |—— _pagination.scss
|            |—— _placeholders.scss
|            |—— _popover.scss
|            |—— _progress.scss
|            |—— _reboot.scss
|            |—— _root.scss
|            |—— _spinners.scss
|            |—— _tables.scss
|            |—— _toasts.scss
|            |—— _tooltip.scss
|            |—— _transitions.scss
|            |—— _type.scss
|            |—— _utilities.scss
|            |—— _variables-dark.scss
|            |—— _variables.scss
|—— package-lock.json
|—— package.json
```

