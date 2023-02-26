<h1><a class="site-title" href="/tsl-mastodon-api/">TypeScript AMD</a></h1>
<table>
    <thead>
        <tr>
            <th>Node Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.amd %}
        <tr>
            <td>
                <a href="https://registry.npmjs.org/@typescriptlibs/amd/-/amd-{{ item.version }}.tgz">tsl-mastodon-api-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
