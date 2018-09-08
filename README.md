# Modul: iFrame
Das iFrame Modul wird benötigt um beliebige Webinhalte auf dem iMirror anzuzeigen. Wie z.B. Videos, Karten uvm.
## Verwendung des Moduls

Um disese Modul zu verwenden muss folgender Code in `config/config.js` eingefügt werden:
````javascript
modules: [
	{
		module: 'iFrame',
		position: 'bottom_bar',	// Dies kann eine beliebige Position sein.
		config: {
			// Siehe Einstellungs Optionen für weitere Informationen.
				url: "Hier URL einfügen"
				width: "100%" // Optional. Default: 100%
				height: "100px" //Optional. Default: 100px
			}
		}
	}
]
````

## Einstellungs Optionen

The following properties can be configured:


<table width="100%">
		<tr>
			<th>Option</th>
			<th width="100%">Description</th>
		</tr>
		<tr>
			<td><code>url</code></td>
			<td>the URL in the iFrame<br>
				<br><b>Example:</b><code>"http:http://example.com/" </code>
				<br><b>Default value:</b> <code>''</code>
			</td>
		</tr>
		<tr>
			<td><code>width</code></td>
			<td>the width of the iFrame<br>
				<br><b>Example:</b><code>"100%"</code>
				<br><b>Example:</b><code>"200px"</code>
				<br><b>Default value:</b> <code>"100%"</code>
			</td>
		</tr>
		<tr>
			<td><code>height</code></td>
			<td>the width of the iFrame<br>
				<br><b>Example:</b><code>"100%"</code>
				<br><b>Example:</b><code>"300px"</code>
				<br><b>Default value:</b> <code>"100px"</code>
			</td>
		</tr>
</table>
