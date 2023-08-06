---
title: Package Downloads
---

<h2><a href="/tst/">TST: TypeScript Tester</a></h2>

<p>
Package Downloads
</p>

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
                <a href="https://registry.npmjs.org/@typescriptlibs/tst/-/tst-{{ item.version }}.tgz">tst-{{ item.version }}.tgz</a>
            </td>
            <td>
                {{ item.checksum }}
            </td>
        </tr>
    {% endfor %}</tbody>
</table>
