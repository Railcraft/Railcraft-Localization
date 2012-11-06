## Welcome to Railcraft's Localization repository on GitHub

### Submitting and editing a language file
If you intend to submit or edit a language file, please be aware that the file must be in UTF-8 encoding without Byte-Order-Marks(BOM).

If you do not know what any of that means, please do some research before submitting a language file.

Notepad++ is the recommend text editor for editing language files because it is capable of saving files in the correct format via the Encoding menu.

Other editors may not save files in the correct format (Notepad, Wordpad, etc...do not).

### Inheritance
When adding language variants from the same family, keep in mind that tags are inherited from the parent language. This should save you a bit of work if parent/child use the same translation.

Please be aware that the inheritance tree does not represent reality, and is simply a construct to simplify translations.

See en_GB for an example of changing just a couple tags and inheriting the rest.

Inheritance:
<ul><li>en_US
	<ul>
	<li>en_GB</li>
	<li>de_DE</li>
	<li>pt_PT
		<ul><li>pt_BR</li></ul>
	</li>
	<li>es_ES
		<ul>
			<li>es_AR</li>
			<li>es_MX</li>
			<li>es_UY</li>
			<li>es_VE</li>	
		</ul>
	</li>
	<li>ru_RU</li>
	<li>fr_FR</li>
	<li>ja_JP</li>
	</ul>
</li></ul>