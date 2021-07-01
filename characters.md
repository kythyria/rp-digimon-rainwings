---
title: "Character Sheets"
---

If you like Google Docs, [here's a template](https://docs.google.com/document/d/1o2T4nCkfbSQMftJ9lGRjm5-VTKA77C6kaHg1GQPpPms/edit?usp=sharing).

If you'd rather submit a pull request, the ones on this site live in the `_characters` directory. They are listed below:

<table>
<thead>
<tr><td>Character</td><td>Player</td></tr>
</thead>
<tbody>
{%- for character in site.characters -%}
<tr>
    <td>
        <a href="{{ character.url }}">{{ character.title }}</a>
    </td>
    <td>{{character.player}}</td>
</tr>
{%- endfor -%}
</tbody>
</table>