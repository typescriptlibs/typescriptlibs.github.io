[RSS TypeScript Library](/tsl-core-rss/)
========================================

<table>
    <thead>
        <tr>
            <th>Node.js Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.tsl-core-rss %}
        <tr>
            <td>
                <a href="https://registry.npmjs.org/tsl-core-rss/-/tsl-core-rss-{{ item.version }}.tgz">tsl-core-rss-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
