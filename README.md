## Git командууд :octocat:

git командуудын тайлбар цагаан толгойн үсгийн дарааллаар харуулав. Нэмэлт мэдээллийг [https://1234.mn/course/108](https://1234.mn/course/108)

**git, github эхнээс нь дуустал** гэдэг сургалт дээр үзсэн командууд болон сурагчдын оролцоотойгоор хөгжүүлэгдэж буй репо юм.

## Командуудын жагсаалт :sparkles:

`git add *` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add .` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add -А` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add [file1.txt] [file2.txt] [*.js]` **file1.txt, file2.txt болон бүх javascript файлуудыг стэйжилнэ**

`git branch` **Бүх бранчуудыг жагсаалтаар харах**

`git branch -a ` **Бүх бранчуудыг үзүүлнэ**

`git branch -r ` **Remote бранчуудыг үзүүлнэ**

`git branch -vv ` **Tracking бранчуудыг үзүүлнэ**

`git commit [--amend]` **Сүүлийн коммитыг засварлах, сайжруулах** `v61|02:30`

`git config user.name [name] ` **Өөрийн нэрийг энд тохируулна (github username байж болно)**

`git config user.email [email_address] ` **Өөрийн имэйлийг энд тохируулна (github username ээ тавьж github руу push хийнэ)**

`git log --oneline` **Идэвхитэй, зөв засагдсан коммитуудын түүхийг харуулна.** `v60|09:47`

`git merge --squash [branch_name]` **branch_name бранчийг одоо байгаа бранч руу merge хийж оруулж ирэхдээ branch_name бранчийн бүх коммитийг нэгтгэн нэг коммит болгож оруулж ирнэ. Хэт бага үйлдэлтэй коммитуудыг нэгтгэн нэг болгоход хэрэглэнэ** `v75`

`git reflog` **Коммитуудын түүхийг жагсаалтаар харах. Репо дээр хийгдсэн өөрчлөлтийн түүхүүд** `v58|03:11`

`git reflog --all` **Коммитуудын түүхийг дэлгэрэнгүй жагсаалтаар харах** `v58|09:59`

`git remote add [remote_name] [remote_url]` **remote_name нэртэй, remote_url хаягтай remote-ийг шинээр үүсгэнэ **

`git remote prune [remote_name]` **Локал дээрх remote_name remote-ийг цэвэрлэнэ** `v45|07:36`

`git reset --hard [hash_code]` **Тухайн hash_code-той коммитруу шилжих, түүнээс хойшхи коммитууд хүчингүй болно** `v58|05:06`

`git reset --hard [HEAD@{number_commit}]` **Тухайн HEAD-ын дугаарыг ашиглан коммитруу шилжих, түүнээс хойшхи коммитууд хүчингүй болно** `v58|05:45`

`git show [hash_code]` **Тухайн коммитын дэлгэрэнгүй мэдээллийг харуулна** `v58|03:46`

`git tag` **Бүх тагуудыг жагсааж үзүүлнэ**

`git tag -l "v0*"` **v0 оор эхэлсэн бүх тагуудыг шүүж үзүүлнэ**
