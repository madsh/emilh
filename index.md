# Emil's side

Her kan du finde navnene på dem jeg spiller med.

Hvis du gerne vil med på listen, så send dit Gamertag på min email <a href="mailto:emilh@me.com?subject='Gamertag til din hjemmeside'">emilh @ me . com</a>.

## Minecraft
<table>
  <thead>
    <tr>
      <th>&nbsp;</th>
      <th>Navn</th>
      <th>Gamertag</th>
    </tr>
  </thead>
  <tbody>
{% for member in site.data.gamers %}
  <tr>
    <td><img width="32" src="{{ member.tag }}.png"/></td>
    <td>{{ member.name }}</td>
    <td><code class="highlighter-rouge">{{ member.tag  }}</code></td>
  </tr>
{% endfor %}
  </tbody>
</table>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

