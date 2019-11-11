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


перебирать номера подряд?

https://ws-public.interpol.int/notices/v1/red/2019-114539
https://ws-public.interpol.int/notices/v1/red/2019-114560
{"arrest_warrants":[{"issuing_country_id":"RU","charge":"Participation in an  illegal armed formation","charge_translation":null}],"weight":null,"forename":"ARSEN","date_of_birth":"1982/12/02","entity_id":"2019/114539","languages_spoken_ids":["ARA","RUS"],"nationalities":["RU"],"height":null,"sex_id":"M","country_of_birth_id":"RU","name":"KURMANBAEV","distinguishing_marks":null,"eyes_colors_id":null,"hairs_id":null,"place_of_birth":"Edige","_embedded":{"links":[]},"_links":{"self":{"href":"https://ws-public.interpol.int/notices/v1/red/2019-114539"},"images":{"href":"https://ws-public.interpol.int/notices/v1/red/2019-114539/images"},"thumbnail":{"href":"https://ws-public.interpol.int/notices/v1/red/2019-114539/images/61610153"}}}


"issuing_country_id":"RU"
"charge":"Participation in an  illegal armed formatio
"forename":"ARSEN",
"date_of_birth":"1982/12
entity_id":"2019/114539"
"sex_id":"M"
"name":"KURMANBAEV"



https://ws-public.interpol.int/notices/v1/red/2019-114560   если пусто то 
{"status":404,"name":"NotFoundError","message":"Not Found"}
