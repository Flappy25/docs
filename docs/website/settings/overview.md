---
slug: /advanced-settings
hide_table_of_contents: true
sidebar_label: Overview
---

# Advanced Settings

Advanced settings allow you to reconfigure your project to do things that Scratch normally wouldn't let you do.

Navigate using the sidebar on the left. Look under the "Advanced settings" category.

<h3>Advanced settings include:</h3>
<h4>Featured</h4>
  Costom FPS
  Interpolation
  High quality pen
  Warp timer
<h4>Remove Limits</h4>
  infinite clones
  Remove fencing
  Remove misc. limits
<h4>Danger Zone</h4>
  Costom stage size
  Disable compiler

<!-- Migration for old links to https://docs.turbowarp.org/advanced-settings#high-quality-pen -->
import BrowserOnly from "@docusaurus/BrowserOnly";
import {Redirect} from "@docusaurus/router";

<BrowserOnly>{() => {
  if (location.hash === "#high-quality-pen") {
    return <Redirect to="high-quality-pen" />;
  }
  return <></>;
}}</BrowserOnly>
