[AMD: TypeScript AMD Loader](/amd/)
===================================

<table>
    <thead>
        <tr>
            <th>Node.js Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.amd %}
        <tr>
            <td>
                <a href="https://registry.npmjs.org/@typescriptlibs/amd/-/amd-{{ item.version }}.tgz">amd-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
