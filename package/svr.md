<h1 class="page-heading"><a href="/svr/">Svr: Simple HTTP(S) Server</a></h1>
<table>
    <thead>
        <tr>
            <th>Node.js Package</th>
            <th>SHA1 Checksum</th>
        </tr>
    </thead>
    <tbody>{% for item in site.data.svr %}
        <tr>
            <td>
                <a href="https://registry.npmjs.org/@typescriptlibs/svr/-/svr-{{ item.version }}.tgz">svr-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
