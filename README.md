# js-StringCompressionByDict

/*
"Here is a complete sample that shows how to create"
"_1 is a co_0te sa_0 that s_3s _3 to create";
*/

let s="_1 is a co_0te sa_0 that s_3s _3 to create";
for(let m of ['m_2','Here','ple','how'].entries()){s=s.replace(RegExp('_'+m[0],'gi'),m[1])};
//

/*
"Here is a complete sample that shows how to create"
"1 i5a co0te sa0 th4 s353 to cre4e"
*/

let s="1 i5a co0te sa0 th4 s353 to cre4e";
for(let m of ['m2','Here','ple','how','at','s '].entries()){s=s.replace(RegExp(m[0],'gi'),m[1])};
