<h1><a class="site-title" href="/tsl-core-json/">JSON TypeScript Library</a></h1>
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
                <a href="https://typescriptlibs.org/npm/tsl-core-json/tsl-core-json-{{ item.version }}.tgz">tsl-core-json-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
