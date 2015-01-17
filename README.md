Mock data for Front-end development
By: Thien Nguyen <nguyenphongthien@gmail.com>

Because we alway do our FE job with designer's data, so we don't know what issues will be happen when we integrate and use real data which aren't alway looking as good as the design. So after integrate, it always take many time to fix bugs. And the way FE dev working on BE view is not always good because of conflict code and make the invalid structure.

So I create this plugin to do the mock data to help us fix that issue.

For the BE dev who do the integration with the html, just remove the plugin and replace every mock data with the BE data, but remember the rule of the data which has been defined by FE dev (like string min length, max length, image size)

This plugin also help FE dev to do their unit test (just simply refresh the page for as many time as you can and bugs - if you have - will appear as mock data are always change after each reload time) and help QAs to test the page once FE done their job without have to wait for the integration