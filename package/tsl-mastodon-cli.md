[Mastodon TypeScript CLI](/tsl-mastodon-cli/)
=============================================

<table>
    <thead>
        <tr>
            <th>Node.js Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.tsl-mastodon-cli %}
        <tr>
            <td>
                <a href="https://registry.npmjs.org/tsl-mastodon-cli/-/tsl-mastodon-cli-{{ item.version }}.tgz">tsl-mastodon-cli-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
