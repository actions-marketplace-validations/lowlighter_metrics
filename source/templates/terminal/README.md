<!--header-->
<table>
  <tr><td colspan="2"><a href="/README.md#%EF%B8%8F-templates">â Back to templates index</a></td></tr>
  <tr><th colspan="2"><h3>đ Terminal template</h3></th></tr>
  <tr><td colspan="2" align="center"><p>A template mimicking a SSH session.</p>
</td></tr>
  <tr>
    <th rowspan="3">Supported features<br><sub><a href="metadata.yml">â Full specification</a></sub></th>
    <td><a href="/source/plugins/screenshot/README.md" title="đ¸ Website screenshot">đ¸</a> <a href="/source/plugins/gists/README.md" title="đĢ Gists">đĢ</a> <a href="/source/plugins/isocalendar/README.md" title="đ Isometric commit calendar">đ</a> <a href="/source/plugins/languages/README.md" title="đˇī¸ Languages activity">đˇī¸</a> <a href="/source/plugins/lines/README.md" title="đ¨âđģ Lines of code changed">đ¨âđģ</a> <a href="/source/plugins/pagespeed/README.md" title="âąī¸ Google PageSpeed">âąī¸</a> <a href="/source/plugins/traffic/README.md" title="đ§Ž Repositories traffic">đ§Ž</a></td>
  </tr>
  <tr>
    <td><code>đ¤ Users</code> <code>đĨ Organizations</code></td>
  </tr>
  <tr>
    <td><code>*ī¸âŖ SVG</code> <code>*ī¸âŖ PNG</code> <code>*ī¸âŖ JPEG</code> <code>#ī¸âŖ JSON</code></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github.com/lowlighter/metrics/blob/examples/metrics.terminal.svg" alt=""></img>
      <img width="900" height="1" alt="">
    </td>
  </tr>
</table>
<!--/header-->

## âšī¸ Examples workflows

<!--examples-->
```yaml
name: Example
uses: lowlighter/metrics@latest
with:
  template: terminal
  filename: metrics.terminal.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: header, metadata

```
<!--/examples-->