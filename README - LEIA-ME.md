# Mod para Minetest

	* Descrição........: Este mod traduz a descrição do item para o idioma definido nas configurações.
	* licença de código: GPLv3+
	* depende..........: nada, exceto todos os mods já utilzados em seu servidor sendo listados em 'depends.txt'. Por isso é carregado após eles.)

## Idiomas atualmente suportados:

	* pt = Português
	* de = Alemão
	* fr = Francês
	* it = Italiano

## Ativando um idioma:

	Para ativar um idioma basta digitar o comando: /set -n language <idioma>

	* Exemplo:  /set -n language <idioma>
	
	Caso nenhum idioma configurado, será setado por padrão o idioma "pt".

## Adicionando um novo idioma

	* Cópia sample_language.lua para seu próprio idioma
	* Renomeá-lo de acordo com seu próprio código de linguagem, em letras maiúsculas
	* Traduzir :)

## Adicionando novas cadeias

	* Primeiro adicioná-los - sem tradução - a sample_language.lua
	* Em seguida, adicioná-los novamente - traduzido, desta vez - para qualquer idioma que você quer / pode.

Dessa forma, outros tradutores só teria que sample_language.lua "diff" para manter o controle de adições.
