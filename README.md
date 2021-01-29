## Git командууд :octocat:

git командуудын тайлбар цагаан толгойн үсгийн дарааллаар. Нэмэлт мэдээллийг [https://1234.mn/course/108](https://1234.mn/course/108)

git эхнээс нь дуустал гэдэг сургалт дээр үзсэн командууд болон сурагчдын оролцоотойгоор хөгжүүлэгдэж буй репо юм.

```javascript
function test() {
  console.log("look ma’, no spaces");
}
```

## Командуудын жагсаалт :sparkles:

`git add *` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add .` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add -А` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add [file.txt]` **file.txt файлыг стэйжилнэ**

`git commit [--amend]` **Сүүлийн коммитыг засварлах, сайжруулах** `v61|02:30`

`git branch` **Бүх бранчуудыг жагсаалтаар харах**

`git branch -a ` **Бүх бранчуудыг үзүүлнэ**

`git branch -r ` **Remote бранчуудыг үзүүлнэ**

`git branch -vv ` **Tracking бранчуудыг үзүүлнэ**

`git config user.name [name] ` **Өөрийн нэрийг энд тохируулна (github username байж болно)**

`git config user.email [email_address] ` **Өөрийн имэйлийг энд тохируулна (github username ээ тавьж github руу push хийнэ)**

`git reflog` **Коммитуудын түүхийг жагсаалтаар харах. Репо дээр хийгдсэн өөрчлөлтийн түүхүүд** `v58|03:11`

`git reflog --all` **Коммитуудын түүхийг дэлгэрэнгүй жагсаалтаар харах** `v58|09:59`

`git log --online` **Идэвхитэй, зөв засагдсан коммитуудын түүхийг харуулна.** `v60|09:47`

`git remote prune [remote_name]` **Локал дээрх remote_name remote-ийг цэвэрлэнэ** `v45|07:36`

`git reset --hard [hash_code]` **Тухайн hash_code-той коммитруу шилжих, түүнээс хойшхи коммитууд хүчингүй болно** `v58|05:06`

`git reset --hard [HEAD@{number_commit}]` **Тухайн HEAD-ын дугаарыг ашиглан коммитруу шилжих, түүнээс хойшхи коммитууд хүчингүй болно** `v58|05:45`

`git show [hash_code]` **Тухайн коммитын дэлгэрэнгүй мэдээллийг харуулна** `v58|03:46`
