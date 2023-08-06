<h1 class="page-heading"><a href="/tsl-mastodon-api/">Mastodon TypeScript Library</a></h1>
<table>
    <thead>
        <tr>
            <th>Node.js Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.tsl-mastodon-api %}
        <tr>
            <td>
                <a href="https://registry.npmjs.org/tsl-mastodon-api/-/tsl-mastodon-api-{{ item.version }}.tgz">tsl-mastodon-api-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
