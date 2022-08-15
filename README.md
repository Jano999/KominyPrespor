Demo verzia kominyprespor.sk

Použité technologie:
HTML,
CSS,
JS,
jQuery,
Bootstrap,
SASS,
PHP

Podstránky sa zatial tvoria jednoducho podla url, načíta sa príslušný PHP súbor z /template/pages/ a príslušné CSS z /assets/css/ (viac v index.php).

V base.scss sa nachádzajú často používané hodnoty ako premenné, pre použitie stačí importnut do daného SCSS súboru.

critical.css sa používa pre above-the-fold sekcie všetkých podstránok (obsah ktorý sa má načítat okamžite).
style.css obsahuje štýly pre below-the-fold sekcie spoločné pre všetky podstránky (napr. pätička stránky).
