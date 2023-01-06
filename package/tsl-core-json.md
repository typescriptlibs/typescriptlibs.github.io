<h1><a class="site-title" href="/tsl-core-json/">TypeScript Library for JSON</a></h1>
<table>
    <thead>
        <tr>
            <th>Node Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.tsl-core-json %}
        <tr>
            <td>
                <a href="https://typescriptlibs.org/npm/tsl-core-json/tsl-core-json-{{ item.version }}.tgz">v{{ item.version }}.tgz</a>
            </td>
            <td>
                <a href="https://typescriptlibs.org/npm/tsl-core-json/tsl-core-json-{{ item.version }}.sha1">{{ item.checksum }}</a>
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
