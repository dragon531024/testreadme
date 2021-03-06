# [Application for Route Managing in SDN](https://demos.creative-tim.com/argon-dashboard-react?ref=adr-github-readme)

![Product Gif](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/argon-dashboard-react/argon-dashboard-react.gif)

Application for Route Managing in SDN เป็น application จัดการเส้นทางของ network ผ่าน topology โดยเน้นการอำนวยความสะดวกของผู้ใช้งาน application

## Table of Contents

- [Tools](#Tools)
- [Demo](#demo)
- [Quick Start](#quick-start)
- [File Structure](#file-structure)
- [Browser Support](#browser-support)
- [Reporting Issues](#reporting-issues)
- [Useful Links](#useful-links)

## Tools

[<img src="https://www.saranitus.com/wp-content/uploads/2014/02/oracle_virtualbox.png" width="60" height="60" />](https://www.virtualbox.org/)[<img src="https://yt3.ggpht.com/ytc/AKedOLTA6YLUPUy6ey3RwtM33DRh8itW_k2j3EuUYhoz=s900-c-k-c0x00ffffff-no-rj" width="60" height="60" />](https://www.opendaylight.org/)[<img src="https://engineering.fb.com/wp-content/uploads/2011/03/Fmj_DAB5qy50-ZgAAEE-EwpuPQkAAAE.jpg" width="60" height="60" />](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/OpenDaylight-Openflow-App/)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/nodejs-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/argon-dashboard-nodejs?ref=adr-github-readme)[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/laravel_logo.png" width="60" height="60" style="background:white"/>](https://www.creative-tim.com/product/argon-dashboard-laravel?ref=adr-github-readme)[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/sketch-logo.jpg" width="60" height="60" />](https://www.creative-tim.com/product/argon-dashboard-react?ref=adr-github-readme)

## Demo

| Dashboard Page                                                                                                                                                                                              | Icons Page                                                                                                                                                                                          | Tables Page                                                                                                                                                                                            | Maps Page                                                                                                                                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [![Dashboard Page](https://github.com/creativetimofficial/public-assets/blob/master/argon-dashboard-react/dashboard-page.png?raw=true)](https://demos.creative-tim.com/argon-dashboard-react/#/admin/index) | [![Icons Page](https://github.com/creativetimofficial/public-assets/blob/master/argon-dashboard-react/icons-page.png?raw=true)](https://demos.creative-tim.com/argon-dashboard-react/#/admin/icons) | [![Tables Page](https://github.com/creativetimofficial/public-assets/blob/master/argon-dashboard-react/tables-page.png?raw=true)](https://demos.creative-tim.com/argon-dashboard-react/#/admin/tables) | [![Maps Page](https://github.com/creativetimofficial/public-assets/blob/master/argon-dashboard-react/maps-page.png?raw=true)](https://demos.creative-tim.com/argon-dashboard-react/#/admin/maps) |

| Register Page                                                                                                                                                                                             | Login Page Page                                                                                                                                                                                         | Profile Page                                                                                                                                                                                                |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [![Login Page](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/argon-dashboard-react/register-page.png)](https://demos.creative-tim.com/argon-dashboard-react/#/auth/register) | [![Login Page Page](https://github.com/creativetimofficial/public-assets/blob/master/argon-dashboard-react/login-page.png?raw=true)](https://demos.creative-tim.com/argon-dashboard-react/#/auth/login) | [![Profile Page](https://github.com/creativetimofficial/public-assets/blob/master/argon-dashboard-react/user-page.png?raw=true)](https://demos.creative-tim.com/argon-dashboard-react/#/admin/user-profile) |

## Quick start

- Clone the repo: `git clone https://github.com/perawitkh/project.git`.
- `npm install --save --legacy-peer-deps`
## File Structure

Within the download you'll find the following directories and files:

```
Application for Route Managing in SDN

project
 ┣ .git
 ┃ ┣ hooks
 ┃ ┃ ┣ applypatch-msg.sample
 ┃ ┃ ┣ commit-msg.sample
 ┃ ┃ ┣ fsmonitor-watchman.sample
 ┃ ┃ ┣ post-update.sample
 ┃ ┃ ┣ pre-applypatch.sample
 ┃ ┃ ┣ pre-commit.sample
 ┃ ┃ ┣ pre-merge-commit.sample
 ┃ ┃ ┣ pre-push.sample
 ┃ ┃ ┣ pre-rebase.sample
 ┃ ┃ ┣ pre-receive.sample
 ┃ ┃ ┣ prepare-commit-msg.sample
 ┃ ┃ ┗ update.sample
 ┃ ┣ info
 ┃ ┃ ┗ exclude
 ┃ ┣ logs
 ┃ ┃ ┣ refs
 ┃ ┃ ┃ ┣ heads
 ┃ ┃ ┃ ┃ ┗ master
 ┃ ┃ ┃ ┗ remotes
 ┃ ┃ ┃ ┃ ┗ origin
 ┃ ┃ ┃ ┃ ┃ ┗ HEAD
 ┃ ┃ ┗ HEAD
 ┃ ┣ objects
 ┃ ┃ ┣ 20
 ┃ ┃ ┃ ┗ 9e7d4716cda4979d24371bdaec3da836f72ad9
 ┃ ┃ ┣ ff
 ┃ ┃ ┃ ┗ 53ea4d34553f3645778f873d6c3c2873e0f641
 ┃ ┃ ┣ info
 ┃ ┃ ┗ pack
 ┃ ┃ ┃ ┣ pack-733e68fd2a7e8dc05c7f272957188bbd3bd9b22e.idx
 ┃ ┃ ┃ ┗ pack-733e68fd2a7e8dc05c7f272957188bbd3bd9b22e.pack
 ┃ ┣ refs
 ┃ ┃ ┣ heads
 ┃ ┃ ┃ ┗ master
 ┃ ┃ ┣ remotes
 ┃ ┃ ┃ ┗ origin
 ┃ ┃ ┃ ┃ ┗ HEAD
 ┃ ┃ ┗ tags
 ┃ ┣ config
 ┃ ┣ description
 ┃ ┣ HEAD
 ┃ ┣ index
 ┃ ┗ packed-refs
 ┣ .github
 ┃ ┗ workflows
 ┃ ┃ ┗ main.yml
 ┣ Documentation
 ┃ ┗ documentation.html
 ┣ public
 ┃ ┣ apple-icon.png
 ┃ ┣ Eroute.png
 ┃ ┣ favicon.ico
 ┃ ┣ index.html
 ┃ ┗ manifest.json
 ┣ src
 ┃ ┣ assets
 ┃ ┃ ┣ css
 ┃ ┃ ┃ ┣ argon-dashboard-react.css
 ┃ ┃ ┃ ┣ argon-dashboard-react.css.map
 ┃ ┃ ┃ ┗ argon-dashboard-react.min.css
 ┃ ┃ ┣ fonts
 ┃ ┃ ┃ ┣ nucleo.eot
 ┃ ┃ ┃ ┣ nucleo.ttf
 ┃ ┃ ┃ ┣ nucleo.woff
 ┃ ┃ ┃ ┗ nucleo.woff2
 ┃ ┃ ┣ img
 ┃ ┃ ┃ ┣ brand
 ┃ ┃ ┃ ┃ ┣ argon-react-white.png
 ┃ ┃ ┃ ┃ ┣ argon-react.png
 ┃ ┃ ┃ ┃ ┣ blue.png
 ┃ ┃ ┃ ┃ ┣ Eroute.png
 ┃ ┃ ┃ ┃ ┣ favicon.png
 ┃ ┃ ┃ ┃ ┗ white.png
 ┃ ┃ ┃ ┣ icons
 ┃ ┃ ┃ ┃ ┗ common
 ┃ ┃ ┃ ┃ ┃ ┣ github.svg
 ┃ ┃ ┃ ┃ ┃ ┗ google.svg
 ┃ ┃ ┃ ┣ theme
 ┃ ┃ ┃ ┃ ┣ angular.jpg
 ┃ ┃ ┃ ┃ ┣ bootstrap.jpg
 ┃ ┃ ┃ ┃ ┣ profile-cover.jpg
 ┃ ┃ ┃ ┃ ┣ react.jpg
 ┃ ┃ ┃ ┃ ┣ sketch.jpg
 ┃ ┃ ┃ ┃ ┣ team-1-800x800.jpg
 ┃ ┃ ┃ ┃ ┣ team-2-800x800.jpg
 ┃ ┃ ┃ ┃ ┣ team-3-800x800.jpg
 ┃ ┃ ┃ ┃ ┣ team-4-800x800.jpg
 ┃ ┃ ┃ ┃ ┗ vue.jpg
 ┃ ┃ ┃ ┗ topopic
 ┃ ┃ ┃ ┃ ┣ host.png
 ┃ ┃ ┃ ┃ ┗ switch.png
 ┃ ┃ ┣ plugins
 ┃ ┃ ┃ ┗ nucleo
 ┃ ┃ ┃ ┃ ┣ css
 ┃ ┃ ┃ ┃ ┃ ┣ nucleo-svg.css
 ┃ ┃ ┃ ┃ ┃ ┗ nucleo.css
 ┃ ┃ ┃ ┃ ┗ fonts
 ┃ ┃ ┃ ┃ ┃ ┣ nucleo-icons.eot
 ┃ ┃ ┃ ┃ ┃ ┣ nucleo-icons.svg
 ┃ ┃ ┃ ┃ ┃ ┣ nucleo-icons.ttf
 ┃ ┃ ┃ ┃ ┃ ┣ nucleo-icons.woff
 ┃ ┃ ┃ ┃ ┃ ┗ nucleo-icons.woff2
 ┃ ┃ ┗ scss
 ┃ ┃ ┃ ┣ argon-dashboard
 ┃ ┃ ┃ ┃ ┣ custom
 ┃ ┃ ┃ ┃ ┃ ┣ alerts
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _alert-dismissible.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _alert.scss
 ┃ ┃ ┃ ┃ ┃ ┣ avatars
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _avatar-group.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _avatar.scss
 ┃ ┃ ┃ ┃ ┃ ┣ badges
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _badge-circle.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _badge-dot.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _badge.scss
 ┃ ┃ ┃ ┃ ┃ ┣ buttons
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _button-brand.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _button-icon.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _button.scss
 ┃ ┃ ┃ ┃ ┃ ┣ cards
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _card-animations.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _card-blockquote.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _card-profile.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _card-stats.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _card.scss
 ┃ ┃ ┃ ┃ ┃ ┣ charts
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _chart.scss
 ┃ ┃ ┃ ┃ ┃ ┣ close
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _close.scss
 ┃ ┃ ┃ ┃ ┃ ┣ custom-forms
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _custom-checkbox.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _custom-control.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _custom-form.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _custom-radio.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _custom-toggle.scss
 ┃ ┃ ┃ ┃ ┃ ┣ dropdowns
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _dropdown.scss
 ┃ ┃ ┃ ┃ ┃ ┣ footers
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _footer.scss
 ┃ ┃ ┃ ┃ ┃ ┣ forms
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _form-validation.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _form.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _input-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ headers
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _header.scss
 ┃ ┃ ┃ ┃ ┃ ┣ icons
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _icon-shape.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _icon.scss
 ┃ ┃ ┃ ┃ ┃ ┣ list-groups
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _list-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ maps
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _map.scss
 ┃ ┃ ┃ ┃ ┃ ┣ masks
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _mask.scss
 ┃ ┃ ┃ ┃ ┃ ┣ mixins
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _alert.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _background-variant.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _badge.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _buttons.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _forms.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _icon.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _modals.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _popover.scss
 ┃ ┃ ┃ ┃ ┃ ┣ modals
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _modal.scss
 ┃ ┃ ┃ ┃ ┃ ┣ navbars
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _navbar-collapse.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _navbar-dropdown.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _navbar-search.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _navbar-vertical.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _navbar.scss
 ┃ ┃ ┃ ┃ ┃ ┣ navs
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _nav-pills.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _nav.scss
 ┃ ┃ ┃ ┃ ┃ ┣ paginations
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _pagination.scss
 ┃ ┃ ┃ ┃ ┃ ┣ popovers
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _popover.scss
 ┃ ┃ ┃ ┃ ┃ ┣ progresses
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _progress.scss
 ┃ ┃ ┃ ┃ ┃ ┣ separators
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _separator.scss
 ┃ ┃ ┃ ┃ ┃ ┣ tables
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _table.scss
 ┃ ┃ ┃ ┃ ┃ ┣ type
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _article.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _display.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _heading.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _type.scss
 ┃ ┃ ┃ ┃ ┃ ┣ utilities
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _backgrounds.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _blurable.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _floating.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _helper.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _image.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _opacity.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _overflow.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _position.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _shadows.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _sizing.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _spacing.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _text.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _transform.scss
 ┃ ┃ ┃ ┃ ┃ ┣ vendors
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _bootstrap-datepicker.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _headroom.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ _nouislider.scss
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ _scrollbar.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _alert.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _avatar.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _badge.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _buttons.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _card.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _chart.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _close.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _components.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _content.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _custom-forms.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _dropdown.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _footer.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _forms.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _functions.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _header.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _icons.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _input-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _list-group.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _map.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _mask.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _mixins.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _modal.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _nav.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _navbar.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _pagination.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _popover.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _progress.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _reboot.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _section.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _separator.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _tables.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _type.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _utilities.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _variables.scss
 ┃ ┃ ┃ ┃ ┃ ┗ _vendors.scss
 ┃ ┃ ┃ ┃ ┗ docs
 ┃ ┃ ┃ ┃ ┃ ┣ _clipboard-js.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _component-examples.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _content.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _footer.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _nav.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _prism.scss
 ┃ ┃ ┃ ┃ ┃ ┣ _sidebar.scss
 ┃ ┃ ┃ ┃ ┃ ┗ _variables.scss
 ┃ ┃ ┃ ┣ react
 ┃ ┃ ┃ ┃ ┣ bootstrap
 ┃ ┃ ┃ ┃ ┃ ┗ _spinners.scss
 ┃ ┃ ┃ ┃ ┣ plugins
 ┃ ┃ ┃ ┃ ┃ ┗ _plugin-react-datetime.scss
 ┃ ┃ ┃ ┃ ┣ react-differences.scss
 ┃ ┃ ┃ ┃ ┣ _buttons.scss
 ┃ ┃ ┃ ┃ ┣ _mixins.scss
 ┃ ┃ ┃ ┃ ┣ _navbar-dropdown.scss
 ┃ ┃ ┃ ┃ ┣ _navbar.scss
 ┃ ┃ ┃ ┃ ┗ _tables.scss
 ┃ ┃ ┃ ┗ argon-dashboard-react.scss
 ┃ ┣ components
 ┃ ┃ ┣ Footers
 ┃ ┃ ┃ ┣ AdminFooter.js
 ┃ ┃ ┃ ┗ AuthFooter.js
 ┃ ┃ ┣ Headers
 ┃ ┃ ┃ ┣ Header.js
 ┃ ┃ ┃ ┗ UserHeader.js
 ┃ ┃ ┣ Navbars
 ┃ ┃ ┃ ┣ AdminNavbar.js
 ┃ ┃ ┃ ┗ AuthNavbar.js
 ┃ ┃ ┣ Sidebar
 ┃ ┃ ┃ ┗ Sidebar.js
 ┃ ┃ ┗ Topology
 ┃ ┃ ┃ ┣ configModal.jsx
 ┃ ┃ ┃ ┣ network.jsx
 ┃ ┃ ┃ ┣ PostConfig.jsx
 ┃ ┃ ┃ ┣ showConfig.jsx
 ┃ ┃ ┃ ┣ thing.jsx
 ┃ ┃ ┃ ┣ TopologyConfig.jsx
 ┃ ┃ ┃ ┗ useWindowSize.js
 ┃ ┣ layouts
 ┃ ┃ ┣ Admin.js
 ┃ ┃ ┗ Auth.js
 ┃ ┣ variables
 ┃ ┃ ┗ charts.js
 ┃ ┣ views
 ┃ ┃ ┣ examples
 ┃ ┃ ┃ ┣ Icons.js
 ┃ ┃ ┃ ┣ Login.js
 ┃ ┃ ┃ ┣ Maps.js
 ┃ ┃ ┃ ┣ Profile.js
 ┃ ┃ ┃ ┣ Register.js
 ┃ ┃ ┃ ┗ Tables.js
 ┃ ┃ ┗ Index.js
 ┃ ┣ index.js
 ┃ ┣ routes.js
 ┃ ┣ store.js
 ┃ ┗ switchSlice.js
 ┣ .gitignore
 ┣ CHANGELOG.md
 ┣ gulpfile.js
 ┣ ISSUE_TEMPLATE.md
 ┣ jsconfig.json
 ┣ LICENSE
 ┣ package-lock.json
 ┣ package.json
 ┗ README.md
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Material Kit. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Kit. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/?ref=adr-github-readme).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.
## Useful Links

- [OpendayFlow Plugin Operation](https://docs.opendaylight.org/projects/openflowplugin/en/latest/users/operation.html?fbclid=IwAR2Ys1w27WjcZITn35I0A39USsjv0uBpLlD49wsDB7lf7P6yF1p9H4LA9xU#flow-id-match-function)

### Social Media

Twitter: <https://twitter.com/CreativeTim?ref=creativetim>

Facebook: <https://www.facebook.com/CreativeTim?ref=creativetim>

Dribbble: <https://dribbble.com/creativetim?ref=creativetim>

Instagram: <https://www.instagram.com/CreativeTimOfficial?ref=creativetim>
