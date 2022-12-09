<h1><a href="/tst/">TST: TypeScript Tester</a></h1>
<table>
    <thead>
        <tr>
            <th>Node Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.tst %}
        <tr>
            <td>
                <a href="https://typescriptlibs.org/npm/tst/v{{ item.version }}.tgz">v{{ item.version }}.tgz</a>
            </td>
            <td>
                <a href="https://typescriptlibs.org/npm/tst/v{{ item.version }}.sha1">{{ item.checksum }}</a>
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
