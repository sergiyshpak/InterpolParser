# InterpolParser
get a list of ppl wanted by RU


https://ws-public.interpol.int/notices/v1/red?arrestWarrantCountryId=RU&resultPerPage=100&page=1

result JSON
	0 - 99
	
	
total - shows total num

res per page is limited 160 entries	


beri po 100..   _links  -> next -> href



чо то глючит гавнина.
на
https://ws-public.interpol.int/notices/v1/red?arrestWarrantCountryId=RU&resultPerPage=100&page=5
выдает вторую страницу

нада брать по 20 результатов чтоле

https://ws-public.interpol.int/notices/v1/red?arrestWarrantCountryId=RU&resultPerPage=20&page=5


сука эти казлы через через json дают только 160 записей.
если брать по 20 то только 8 страниц

если по 100 то две страницы

{"total":2652,"query":{"page":5,"resultPerPage":20,"arrestWarrantCountryId":"RU"},"_embedded":{"notices

сука менты галимые

и через веб тоже.
8 экранов по 20 человек на каждом.
дальше уже фсьо.
факаные пигсы
