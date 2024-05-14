<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="/PhoebusSi/Alpaca-CoT/blob/main/CN_README.md"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/PhoebusSi/Alpaca-CoT/blob/main/README.md"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语</font></font></strong></a></p>
<div id="user-content-top" dir="auto"></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/Alpaca-CoT-2.jpg"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/Alpaca-CoT-2.jpg" alt="羊驼毛CoT" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Alpaca-CoT：具有统一指令收集接口、参数高效方法和大型语言模型的指令调优平台</font></font></h1><a id="user-content-alpaca-cot-an-instruction-tuning-platform-with-unified-interface-for-instruction-collection-parameter-efficient-methods-and-large-language-models" class="anchor" aria-label="永久链接：Alpaca-CoT：具有统一指令收集接口、参数高效方法和大型语言模型的指令调优平台" href="#alpaca-cot-an-instruction-tuning-platform-with-unified-interface-for-instruction-collection-parameter-efficient-methods-and-large-language-models"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/PhoebusSi/Alpaca-CoT/blob/main/LICENSE.txt"><img src="https://camo.githubusercontent.com/40c66bbaea491733930e37a4f33928922d8deab0c56adef1c7d3c736cf62f52b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f50686f6562757353692f416c706163612d436f54" alt="执照" data-canonical-src="https://img.shields.io/github/license/PhoebusSi/Alpaca-CoT" style="max-width: 100%;"></a>
<a href="https://pytorch.org/" rel="nofollow"><img src="https://camo.githubusercontent.com/80f6635ce60f0384b2f5f671e297fddedd123ae29ccb12212bb6b83ea852a83f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f7079746f7263682d2533453d312e31332d7265643f6c6f676f3d7079746f726368" alt="火炬" data-canonical-src="https://img.shields.io/badge/pytorch-%3E=1.13-red?logo=pytorch" style="max-width: 100%;"></a>
<a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT" rel="nofollow"><img src="https://camo.githubusercontent.com/58b9c297a9888d13ebd39c3c7656c8dedb8abf61ba9ed8db18e7745d74ade6ee/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f68756767696e67666163652d646174617365742d79656c6c6f773f6c6f676f3d646174613a696d6167652f706e673b6261736536342c6956424f5277304b47676f414141414e53556845556741414143414141414167434159414141427a656e7230414141414247644254554541414c4750432f7868425141414143426a53464a4e414142364a6741416749514141506f41414143413641414164544141414f7067414141366d41414146334363756c453841414141426d4a4c523051412f77442f41502b67766165544141414a58556c45515652594351584265577a573933334138546659514942414d4f61302f58782b514a5a6f61524a495170757379534a5361474b59306e577052725a566d54713155672b742f7a5264322f327a7155762f574e644b5739524e33535a7455374e70556d7177755179476d5073776c2f48782f543063375a495753696867472f5034656e7867502b2b39586741414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141415044524856662b7573396e622f6237796d38473358527a3050585862726b4d41414141414141414141414141414141414141414141414141414141414943502b337838594e692f6e5a6e78714f5750623375766338722b3439702f53752b6e5353667666547778365a482b6f6370333770557242514141414141414141414141414141414141414141414141507248724273712b362b4f666a546f6a5a2f6f6d566531645a57327a4e506d3264705370627357614e746137667854766474735a57726f546d6e4548366b31414141414141414141414141414141414141414139412f354f616448502f536a482b712b6c64714374732f586a6d5861576164643958717058692b73316c4e4c7457324f376b54624e326a2f4871656d765677752b784941414141414141414141414141414141412f61584b31787a2f734f794a6c33556e65724a47657770617a4454504e412f4e512f5051504e4d38307a7a54726e7239594b45327a644c30545858792f76435962774141414141414141414141414141634b666b6e7a6c3264644b326462717657727361744a6870436b32684b545346707441556d6b4a546141724e5134755a6e6c75704f39467a58334447795a475263543844414141414141414141414441627766385247577172382f327037523172766147357145704e49576d30425361516c4e6f436b32684b5453467074415557737930733035336f6a316664584c613334794f566c594441414141414141416f4d34656e33532f36537536432b307061423661516c4e6f4d545150546145704e49576d30425361516f75686557674b54614846544d2b74306961306634656c4d6638624141414141414141674a7633334f624130526c337a745a7a4b7a58504e49576d30474a34372f5136703373794c59616d30425361516c4e6f736544676d62564f645764614c47674b54614846544938733067507239454670664854555a77414141414141414269666371655833745439637a54504e49576d73484b3534482f392f624e752f737757332f377169343563574b4e356141704e6f56634b2f767a644457375a764d5676664f6e3376646578566f75684b545346646864304a3372375a77364f2b4f38414141414141467935586c6c64476272573539346c656e614635706d6d3044776376376a473137647439706c504e727268755559763766686476564c51464a7148307a33686d32397363735047527039365a717648336e74537278593068616251597159667a4e645457357a52583937534251414141414263372f4e31623732767a57685051564e6f436b316870526a2b772f632b35512b2f39377a482f7563544470355a71336c6f436b32684b547a372f6850752b656e5466766d4c4c2f7662343439714d545346707441383037504c64552b4e6a7431343048652f3868774141414141742b2f3758662f76373354764c4d307a546145704e49586d3455787657456d6831786f30443032684b5453467074417242623153634b6f7230324a6f436b32684b545150765653767a624e31714d502b6b6c38454141414159484445483176387568366f316a7a54464a70435532674b54614635364e57435869356f436b32684b545150765672517977584e51314e6f436b32684b545346396853304252335936353337666873414141434155746c2f4d6e314644383752504e4d556d6b4a54614171395776446f65302f367a7473762b4973446a326d786f4c396f3047734e6a6e577563642b2f50653333762f5743355974724e41394e6f536b30686162516e6f4b326f48334e3368333272774541414143344e2b495076506f7433543962693273307a7a54504e49586d6f64634b48767250703378797731593362667173662f6e6c6c2f7a48762f6d6b372f7a563832372f6f30302b73374852375a392f78616e7554504e4d383941556d6d65615a39705430475a30384a4439773556764141414141484439627558507666345433595565713947326864717851764e4d4f2b753075383642302b76386738624e50767643613737366534322b2b48796a5731356f394f5650762b62366a59332b792f633336725743647462707058724e51302f566174744350627859572b6270634b72637675387241414141324e52556462666b7577363061394d7362616e57746f5861584b304848396157616d32753167753137766a7065722f30306c592f33507035327874667433666235327a662f49642b6266736d427a725736636b6133566d6c752b5a6f32304a747274613268626f44335238364d54417a4e4f59506247717141674267714f7933485479672b782f5670746d366435376d6d5236723066646e3662456150664b493770366a65594f6c2f313376324465334f5072574e6b662b5971766a37377a6b784f6c487462644f6d36763178464a745836512f6e36566e6c6d6c765156757164636338506252657931304f6c58306267436174636d6171302b4d6239654138505647724c58503036424c4e4d3232647232655761302b444e6c66727956713946707243796f57315669367430537346765a4c703455643039317a4e4d7a31576f346365316d4b6d6878627037726c3661706e756d365558336e423871704b616d71784372564a3750506d79747337566e6f4a323165762b2b587069715635637261337a746274426a793352356d7139564b6435706e6c6f4870706e656e366c37717a53303875307330356248394b75656a323857413875314e3643646a586f72746c363653334c6b313556713768787a7963747052483331577272664731646f4b6558613239425031696b486376315749326571745555326a70663938375437675a4e6f586d6d6e5858614d6b635050617835706b6558364b6c6150566d7252783752336f49657239563938335866504433344f31596d2b6f5948686e3243572f6473645043304e732f5738367530753047504c4e4644692f52536e586256613535704373314475787430393178745836783570696e3077414a7466556837433570435532696561566539586c797462512f723861586157394454793354584968332f746155525038764e51546459756a7a70376f5861746c43504c39554c712f58384b72323457764e4d5532674b5461484654452f5736753435326c7651726e70747274617a4b7a54504e49576d304253615a33702b6c563559726564583662476c3276715137692f6f52502f6b794b52506333764146787a73314a327a74474f35646a586f6b526f3975314b4c6d616251464a70435532677830784e4c646339637a54507461644357616a323751764e4d5532674b54614570744a6a7071655636624b6c32462f544545743239524d75334c493156507358416749746e5a727a693165396f453370776e6c3559706232687855794c6d65615a35706b574d2b3175304e3156326f496557614348352b734f7448576570744269706e6d6d6561624654504e4d6577703662715565714e596431587239585363662b4574314551446c7163714c307a502b796e7348394e537232767951376b49507a7455546a2b695a5a64717854493876316861303754487466464d3758744f7a323754724c643158703376514530753059376d657164586a693756746a7261677578627032532f6f63496454303136666d764c54414141416a493557567066472f4c48364b30654c65754f6639634a3262562b767266586157716366724e6372333958795463636e505445393765477036557237324b54484862367376562f5851302f6f76745861577444447a326e6e572f7278662b6a34527a3659397362777544395356774541414141414146417157564d71752f332b694f2b4e54396c546d5a363434336a2f6d4f4e3935637230784a335243552b574a39304f41414141554372374a324d546e7167384b4e39782f47375a695947787976546b6e664b4576615578667a593835682b5853745941414141414141414141414141414b444f4868353265642b516a77314e2b506a74455663414141414141414141414e77656363585168492f3344666e59384c444c31646b4141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414438503848537734454d6c505a68414141414a5852465748526b5958526c4f6d4e795a5746305a5141794d44497a4c5441304c544579564445794f6a49304f6a51784b7a41774f6a4177556d4e677541414141435630525668305a4746305a547074623252705a6e6b414d6a41794d7930774e4330784d6c51784d6a6f794e446f304d5373774d446f774d434d2b324151414141416f64455659644752686447553664476c745a584e3059573177414449774d6a4d744d4451744d544a554d5449364d6a51364e4445724d4441364d4442304b2f6e624141414141456c46546b5375516d4343" alt="数据" data-canonical-src="https://img.shields.io/badge/huggingface-dataset-yellow?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAABmJLR0QA/wD/AP+gvaeTAAAJXUlEQVRYCQXBeWzW933A8TfYQIBAMOa0/Xx+QJZoaRJIQpusySJSaGKY0nWpRrZVmTq1Ug+t/zRd2/2zqUv/WNdKW9RN3SZtU7NpUmqwuQyGmPswl/Hx/T0c7ZIWSihgG/P4enxgP++9XgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPDRHVf+us9nb/b7ym8G3XRz0PXXbrkMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAICP+3x8YNi/nZnxqOWPb3uvc8r+49p/Su+nSSfvfTwx6ZH+ocp37pUrBQAAAAAAAAAAAAAAAAAAAAAAAPrHrBsq+6+OfjTojZ/omVe1dZW2zNPm2dpSpbsWaNta7fxTvdtsZWroTmnEH6k1AAAAAAAAAAAAAAAAAAAA9A/5OadHP/SjH+q+ldqCts/XjmXaWadd9XqpXi+s1lNLtW2O7kTbN2j/HqemvVwu+xIAAAAAAAAAAAAAAAAA/aXK1xz/sOyJl3UnerJGewpazDTPNA/NQ/PQPNM80zzTrnr9YKE2zdL0TXXy/vCYbwAAAAAAAAAAAAAAcKfknzl2ddK2dbqvWrsatJhpCk2hKTSFptAUmkJTaArNQ4uZnlupO9FzX3DGyZGRcT8DAAAAAAAAAADAbwf8RGWqr8/2p7R1rvaG5qEpNIWm0BSaQlNoCk2hKTSFptAUWsy0s053oj1fdXLa34yOVlYDAAAAAAAAoM4en3S/6Su6C+0paB6aQlNoMTQPTaEpNIWm0BSaQouheWgKTaHFTM+t0ia0f4elMf8bAAAAAAAAgJv33ObA0Rl3ztZzKzXPNIWm0GJ47/Q6p3syLYam0BSaQlNoseDgmbVOdWdaLGgKTaHFTI8s0gPr9EFpfHTUZwAAAAAAABifcqeX3tT9czTPNIWmsHK54H/9/bNu/swW3/7qi45cWKN5aApNoVcK/vzdDW7ZvMVvfOn3vdexVouhKTSFdhd0J3r7Zw6O+O8AAAAAAFy5XlldGbrW594lenaF5pmm0Dwcv7jG17dt9plPNrrhuUYv7fhdvVLQFJqH0z3hm29scsPGRp96ZqvH3ntSrxY0habQYqYfzNdTW5zRX97SBQAAAABc7/N1b72vzWhPQVNoCk1hpRj+w/c+5Q+/97zH/ucTDp5Zq3loCk2hKTz7/hPu+enTfvmLL/vb449qMTSFptA807PLdU+Njt140He/8hwAAAAAt+/7Xf/v73TvLM0zTaEpNIXm4UxvWEmh1xo0D02hKTSFptArBb1ScKor02JoCk2hKTQPvVSvzbN1qMP+kl8EAAAAYHDEH1v8uh6o1jzTFJpCU2gKTaF56NWCXi5oCk2hKTQPvVrQywXNQ1NoCk2hKTSF9hS0BR3Y6537fhsAAACAUtl/Mn1FD87RPNMUmkJTaAq9WvDoe0/6ztsv+IsDj2mxoL9o0GsNjnWucd+/Pe33v/WC5YtrNA9NoSk0habQnoK2oH3N3h32rwEAAAC4N+IPvPot3T9bi2s0zzTPNIXmodcKHvrPp3xyw1Y3bfqsf/nll/zHv/mk7/zV827/o00+s7HR7Z9/xanuTPNM89AUmmeaZ9pT0GZ08JD9w5VvAAAAAHD9buXPvf4T3YUeq9G2hdqxQvNMO+u0u86B0+v8g8bNPvvCa776e42++HyjW15o9OVPv+b6jY3+y/c36rWCdtbppXrNQ0/VattCPbxYW+bpcKrcvu8rAAAA2NRUdbfkuw60a9MsbanWtoXaXK0HH9aWam2u1gu17vjper/00lY/3Pp52xtft3fb52zf/Id+bfsmBzrW6cka3Vmlu+Zo20Jtrta2hboD3R86MTAzNOYPbGqqAgBgqOy3HTyg+x/Vptm6d57mmR6r0fdn6bEaPfKI7p6jeYOl/13v2De3OPrWNkf+Yqvj77zkxOlHtbdOm6v1xFJtX6Q/n6VnlmlvQVuqdcc8PbRey10OlX0bgCatcmaq0+Mb9eA8PVGrLXP06BLNM22dr2eWa0+DNlfryVq9FprCyoW1Vi6t0SsFvZLp4Ud091zNMz1Wo4ce1mKmhxbp7rl6apnum6UX3nB8qpKamqxCrVJ7PPmyts7VnoJ21ev++XpiqV5cra3ztbtBjy3R5mq9VKd5pnloHppnen6l7qzS08u0s05bH9Kuej28WA8u1N6CdjXortl66S3Lk15Vq7hxzyctpRH31WrrfG1doKeXa29BP1ikHcv1WI2eqtUU2jpf987T7gZNoXmmnXXaMkcPPax5pkeX6KlaPVmrRx7R3oIer9V983XfPD34O1Ym+oYHhn2CW/dsdPC0Ns/W86u0u0GPLNFDi/RSnXbVa55pCs1Duxt091xtX6x5pin0wAJtfUh7C5pCU2ieaVe9XlytbQ/r8aXaW9DTy3TXIh3/taURP8vNQTdYujzp7oXatlCPL9ULq/X8Kr24WvNMU2gKTaHFTE/W6u452lvQrnptrtazKzTPNIWm0BSaZ3p+lV5YredX6bGl2vqQ7i/oRP/kyKRPc3vAFxzs1J2ztGO5djXokRo9u1KLmabQFJpCU2gx0xNLdc9czTPtadCWaj27QvNMU2gKTaEptJjpqeV6bKl2F/TEEt29RMu3LI1VPsXAgItnZrzi1e9oE3pwnl5Ypb2hxUyLmeaZ5pkWM+1u0N1V2oIeWaCH5+sOtHWeptBipnmmeabFTPNMewp6bqUeqNYd1Xr9XScf+Et1EQDlqcqL0zP+ynsH9NSr2vyQ7kIPztUTj+iZZdqxTI8v1ha07THtfFM7XtOz27TrLd1Xp3vQE0u0Y7meqdXji7Vtjraguxbp2S/ocIdT016fmvLTAAAAjI5WVpfG/LH6K0eLeuOf9cJ2bV+vrfXaWqcfrNcr39XyTccnPTE97eGp6Ur72KTHHb6svV/XQ0/ovtXaWtDDz2nnW/rxf+j4Rz6Y9sbwuD9SVwEAAAAAAFAqWVMqu/3+iO+NT9lTmZ6443j/mON95cr0xJ3RCU+WJ90OAAAAUCr7J2MTnqg8KN9x/G7ZiYGxyvTknfKEvaUxfzY85h+XStYAAAAAAAAAAAAAAKDOHh52ed+Qjw1N+PjtEVcAAAAAAAAAANweccXQhI/3DfnY8LDL1dkAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD8P8HSw4EMlPZhAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDIzLTA0LTEyVDEyOjI0OjQxKzAwOjAwUmNguAAAACV0RVh0ZGF0ZTptb2RpZnkAMjAyMy0wNC0xMlQxMjoyNDo0MSswMDowMCM+2AQAAAAodEVYdGRhdGU6dGltZXN0YW1wADIwMjMtMDQtMTJUMTI6MjQ6NDErMDA6MDB0K/nbAAAAAElFTkSuQmCC" style="max-width: 100%;"></a>
<a href="https://huggingface.co/QingyiSi/Alpaca-CoT" rel="nofollow"><img src="https://camo.githubusercontent.com/2be0886772e8661ada16ebfb7e59038dc890270bdb151f87702d4793b561d021/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f68756767696e67666163652d6d6f64656c2d79656c6c6f773f6c6f676f3d646174613a696d6167652f706e673b6261736536342c6956424f5277304b47676f414141414e53556845556741414143414141414167434159414141427a656e7230414141414247644254554541414c4750432f7868425141414143426a53464a4e414142364a6741416749514141506f41414143413641414164544141414f7067414141366d41414146334363756c453841414141426d4a4c523051412f77442f41502b67766165544141414a58556c45515652594351584265577a573933334138546659514942414d4f61302f58782b514a5a6f61524a495170757379534a5361474b59306e577052725a566d54713155672b742f7a5264322f327a7155762f574e644b5739524e33535a7455374e70556d7177755179476d5073776c2f48782f543063375a495753696867472f5034656e7867502b2b39586741414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141415044524856662b7573396e622f6237796d38473358527a3050585862726b4d41414141414141414141414141414141414141414141414141414141414943502b337838594e692f6e5a6e78714f5750623375766338722b3439702f53752b6e5353667666547778365a482b6f6370333770557242514141414141414141414141414141414141414141414141507248724273712b362b4f666a546f6a5a2f6f6d566531645a57327a4e506d3264705370627357614e746137667854766474735a57726f546d6e4548366b31414141414141414141414141414141414141414139412f354f616448502f536a482b712b6c64714374732f586a6d5861576164643958717058692b73316c4e4c7457324f376b54624e326a2f4871656d765677752b784941414141414141414141414141414141412f61584b31787a2f734f794a6c33556e65724a47657770617a4454504e412f4e512f5051504e4d38307a7a54726e7239594b45327a644c30545858792f76435962774141414141414141414141414141634b666b6e7a6c3264644b326462717657727361744a6870436b32684b545346707441556d6b4a546141724e5134755a6e6c75704f39467a58334447795a475263543844414141414141414141414441627766385247577172382f327037523172766147357145704e49576d30425361516c4e6f436b32684b5453467074415557737930733035336f6a316664584c613334794f566c594441414141414141416f4d34656e33532f36537536432b307061423661516c4e6f4d545150546145704e49576d30425361516f75686557674b54614846544d2b74306961306634656c4d6638624141414141414141674a7633334f624130526c337a745a7a4b7a58504e49576d30474a34372f5136703373794c59616d30425361516c4e6f736544676d62564f645764614c47674b54614846544938733067507239454670664854555a77414141414141414269666371655833745439637a54504e49576d73484b3534482f392f624e752f737757332f377169343563574b4e356141704e6f56634b2f767a644457375a764d5676664f6e3376646578566f75684b545346646864304a3372375a77364f2b4f38414141414141467935586c6c64476272573539346c656e614635706d6d3044776376376a473137647439706c504e727268755559763766686476564c51464a7148307a33686d32397363735047527039365a717648336e74537278593068616251597159667a4e645457357a52583937534251414141414263372f4e31623732767a57685051564e6f436b316870526a2b772f632b35512b2f39377a482f7563544470355a71336c6f436b32684b547a372f6850752b656e5466766d4c4c2f7662343439714d545346707441383037504c64552b4e6a7431343048652f3868774141414141742b2f3758662f76373354764c4d307a546145704e49586d3455787657456d6831786f30443032684b5453467074417242623153634b6f7230324a6f436b32684b545150765653767a624e31714d502b6b6c38454141414159484445483176387568366f316a7a54464a70435532674b54614635364e57435869356f436b32684b545150765672517977584e51314e6f436b32684b545346396853304252335936353337666873414141434155746c2f4d6e314644383752504e4d556d6b4a54614171395776446f65302f367a7473762b4973446a326d786f4c396f3047734e6a6e577563642b2f50653333762f5743355974724e41394e6f536b30686162516e6f4b326f48334e3368333272774541414143344e2b495076506f7433543962693273307a7a54504e49586d6f64634b48767250703378797731593362667173662f6e6c6c2f7a48762f6d6b372f7a563832372f6f30302b73374852375a392f78616e7554504e4d383941556d6d65615a39705430475a30384a4439773556764141414141484439627558507666345433595565713947326864717851764e4d4f2b753075383642302b76386738624e50767643613737366534322b2b48796a5731356f394f5650762b62366a59332b792f633336725743647462707058724e51302f566174744350627859572b6270634b72637675387241414141324e52556462666b7577363061394d7362616e57746f5861584b304848396157616d32753167753137766a7065722f30306c592f33507035327874667433666235327a662f49642b6266736d427a725736636b6133566d6c752b5a6f32304a747274613268626f44335238364d54417a4e4f59506247717141674267714f7933485479672b782f5670746d366435376d6d5236723066646e3662456150664b493770366a65594f6c2f313376324465334f5072574e6b662b5971766a37377a6b784f6c487462644f6d36763178464a745836512f6e36566e6c6d6c765156757164636338506252657931304f6c58306267436174636d6171302b4d6239654138505647724c58503036424c4e4d3232647232655761302b444e6c66727956713946707243796f57315669367430537346765a4c703455643039317a4e4d7a31576f346365316d4b6d6878627037726c3661706e756d365558336e423871704b616d71784372564a3750506d79747337566e6f4a323165762b2b587069715635637261337a746274426a793352356d7139564b6435706e6c6f4870706e656e366c37717a53303875307330356248394b75656a323857413875314e3643646a586f72746c363653334c6b313556713768787a7963747052483331577272664731646f4b6558613239425031696b486376315749326571745555326a70663938375437675a4e6f586d6d6e5858614d6b635050617835706b6558364b6c6150566d7252783752336f49657239563938335866504433344f31596d2b6f5948686e3243572f6473645043304e732f5738367530753047504c4e4644692f52536e586256613535704373314475787430393178745836783570696e3077414a7466556837433570435532696561566539586c797462512f723861586157394454793354584968332f746155525038764e51546459756a7a70376f5861746c43504c39554c712f58384b72323457764e4d5532674b5461484654452f5736753435326c7651726e70747274617a4b7a54504e49576d304253615a33702b6c563559726564583662476c3276715137692f6f52502f6b794b52506333764146787a73314a327a74474f35646a586f6b526f3975314b4c6d616251464a70435532677830784e4c646339637a54507461644357616a323751764e4d5532674b54614570744a6a7071655636624b6c32462f544545743239524d75334c493156507358416749746e5a727a693165396f453370776e6c3559706232687855794c6d65615a35706b574d2b3175304e3156326f496557614348352b734f7448576570744269706e6d6d6561624654504e4d6577703662715565714e596431587239585363662b4574314551446c7163714c307a502b796e7348394e537232767951376b49507a7455546a2b695a5a64717854493876316861303754487466464d3758744f7a323754724c643158703376514530753059376d657164586a693756746a7261677578627032532f6f63496454303136666d764c54414141416a493557567066472f4c48364b30654c65754f6639634a3262562b767266586157716366724e6372333958795463636e505445393765477036557237324b54484862367376562f5851302f6f76745861577444447a326e6e572f7278662b6a34527a3659397362777544395356774541414141414146417157564d71752f332b694f2b4e54396c546d5a363434336a2f6d4f4e3935637230784a335243552b574a39304f41414141554372374a324d546e7167384b4e39782f47375a695947787976546b6e664b4576615578667a593835682b5853745941414141414141414141414141414b444f4868353265642b516a77314e2b506a74455663414141414141414141414e77656363585168492f3344666e59384c444c31646b4141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414141414438503848537734454d6c505a68414141414a5852465748526b5958526c4f6d4e795a5746305a5141794d44497a4c5441304c544579564445794f6a49304f6a51784b7a41774f6a4177556d4e677541414141435630525668305a4746305a547074623252705a6e6b414d6a41794d7930774e4330784d6c51784d6a6f794e446f304d5373774d446f774d434d2b324151414141416f64455659644752686447553664476c745a584e3059573177414449774d6a4d744d4451744d544a554d5449364d6a51364e4445724d4441364d4442304b2f6e624141414141456c46546b5375516d4343" alt="模型" data-canonical-src="https://img.shields.io/badge/huggingface-model-yellow?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAABmJLR0QA/wD/AP+gvaeTAAAJXUlEQVRYCQXBeWzW933A8TfYQIBAMOa0/Xx+QJZoaRJIQpusySJSaGKY0nWpRrZVmTq1Ug+t/zRd2/2zqUv/WNdKW9RN3SZtU7NpUmqwuQyGmPswl/Hx/T0c7ZIWSihgG/P4enxgP++9XgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPDRHVf+us9nb/b7ym8G3XRz0PXXbrkMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAICP+3x8YNi/nZnxqOWPb3uvc8r+49p/Su+nSSfvfTwx6ZH+ocp37pUrBQAAAAAAAAAAAAAAAAAAAAAAAPrHrBsq+6+OfjTojZ/omVe1dZW2zNPm2dpSpbsWaNta7fxTvdtsZWroTmnEH6k1AAAAAAAAAAAAAAAAAAAA9A/5OadHP/SjH+q+ldqCts/XjmXaWadd9XqpXi+s1lNLtW2O7kTbN2j/HqemvVwu+xIAAAAAAAAAAAAAAAAA/aXK1xz/sOyJl3UnerJGewpazDTPNA/NQ/PQPNM80zzTrnr9YKE2zdL0TXXy/vCYbwAAAAAAAAAAAAAAcKfknzl2ddK2dbqvWrsatJhpCk2hKTSFptAUmkJTaArNQ4uZnlupO9FzX3DGyZGRcT8DAAAAAAAAAADAbwf8RGWqr8/2p7R1rvaG5qEpNIWm0BSaQlNoCk2hKTSFptAUWsy0s053oj1fdXLa34yOVlYDAAAAAAAAoM4en3S/6Su6C+0paB6aQlNoMTQPTaEpNIWm0BSaQouheWgKTaHFTM+t0ia0f4elMf8bAAAAAAAAgJv33ObA0Rl3ztZzKzXPNIWm0GJ47/Q6p3syLYam0BSaQlNoseDgmbVOdWdaLGgKTaHFTI8s0gPr9EFpfHTUZwAAAAAAABifcqeX3tT9czTPNIWmsHK54H/9/bNu/swW3/7qi45cWKN5aApNoVcK/vzdDW7ZvMVvfOn3vdexVouhKTSFdhd0J3r7Zw6O+O8AAAAAAFy5XlldGbrW594lenaF5pmm0Dwcv7jG17dt9plPNrrhuUYv7fhdvVLQFJqH0z3hm29scsPGRp96ZqvH3ntSrxY0habQYqYfzNdTW5zRX97SBQAAAABc7/N1b72vzWhPQVNoCk1hpRj+w/c+5Q+/97zH/ucTDp5Zq3loCk2hKTz7/hPu+enTfvmLL/vb449qMTSFptA807PLdU+Njt140He/8hwAAAAAt+/7Xf/v73TvLM0zTaEpNIXm4UxvWEmh1xo0D02hKTSFptArBb1ScKor02JoCk2hKTQPvVSvzbN1qMP+kl8EAAAAYHDEH1v8uh6o1jzTFJpCU2gKTaF56NWCXi5oCk2hKTQPvVrQywXNQ1NoCk2hKTSF9hS0BR3Y6537fhsAAACAUtl/Mn1FD87RPNMUmkJTaAq9WvDoe0/6ztsv+IsDj2mxoL9o0GsNjnWucd+/Pe33v/WC5YtrNA9NoSk0habQnoK2oH3N3h32rwEAAAC4N+IPvPot3T9bi2s0zzTPNIXmodcKHvrPp3xyw1Y3bfqsf/nll/zHv/mk7/zV827/o00+s7HR7Z9/xanuTPNM89AUmmeaZ9pT0GZ08JD9w5VvAAAAAHD9buXPvf4T3YUeq9G2hdqxQvNMO+u0u86B0+v8g8bNPvvCa776e42++HyjW15o9OVPv+b6jY3+y/c36rWCdtbppXrNQ0/VattCPbxYW+bpcKrcvu8rAAAA2NRUdbfkuw60a9MsbanWtoXaXK0HH9aWam2u1gu17vjper/00lY/3Pp52xtft3fb52zf/Id+bfsmBzrW6cka3Vmlu+Zo20Jtrta2hboD3R86MTAzNOYPbGqqAgBgqOy3HTyg+x/Vptm6d57mmR6r0fdn6bEaPfKI7p6jeYOl/13v2De3OPrWNkf+Yqvj77zkxOlHtbdOm6v1xFJtX6Q/n6VnlmlvQVuqdcc8PbRey10OlX0bgCatcmaq0+Mb9eA8PVGrLXP06BLNM22dr2eWa0+DNlfryVq9FprCyoW1Vi6t0SsFvZLp4Ud091zNMz1Wo4ce1mKmhxbp7rl6apnum6UX3nB8qpKamqxCrVJ7PPmyts7VnoJ21ev++XpiqV5cra3ztbtBjy3R5mq9VKd5pnloHppnen6l7qzS08u0s05bH9Kuej28WA8u1N6CdjXortl66S3Lk15Vq7hxzyctpRH31WrrfG1doKeXa29BP1ikHcv1WI2eqtUU2jpf987T7gZNoXmmnXXaMkcPPax5pkeX6KlaPVmrRx7R3oIer9V983XfPD34O1Ym+oYHhn2CW/dsdPC0Ns/W86u0u0GPLNFDi/RSnXbVa55pCs1Duxt091xtX6x5pin0wAJtfUh7C5pCU2ieaVe9XlytbQ/r8aXaW9DTy3TXIh3/taURP8vNQTdYujzp7oXatlCPL9ULq/X8Kr24WvNMU2gKTaHFTE/W6u452lvQrnptrtazKzTPNIWm0BSaZ3p+lV5YredX6bGl2vqQ7i/oRP/kyKRPc3vAFxzs1J2ztGO5djXokRo9u1KLmabQFJpCU2gx0xNLdc9czTPtadCWaj27QvNMU2gKTaEptJjpqeV6bKl2F/TEEt29RMu3LI1VPsXAgItnZrzi1e9oE3pwnl5Ypb2hxUyLmeaZ5pkWM+1u0N1V2oIeWaCH5+sOtHWeptBipnmmeabFTPNMewp6bqUeqNYd1Xr9XScf+Et1EQDlqcqL0zP+ynsH9NSr2vyQ7kIPztUTj+iZZdqxTI8v1ha07THtfFM7XtOz27TrLd1Xp3vQE0u0Y7meqdXji7Vtjraguxbp2S/ocIdT016fmvLTAAAAjI5WVpfG/LH6K0eLeuOf9cJ2bV+vrfXaWqcfrNcr39XyTccnPTE97eGp6Ur72KTHHb6svV/XQ0/ovtXaWtDDz2nnW/rxf+j4Rz6Y9sbwuD9SVwEAAAAAAFAqWVMqu/3+iO+NT9lTmZ6443j/mON95cr0xJ3RCU+WJ90OAAAAUCr7J2MTnqg8KN9x/G7ZiYGxyvTknfKEvaUxfzY85h+XStYAAAAAAAAAAAAAAKDOHh52ed+Qjw1N+PjtEVcAAAAAAAAAANweccXQhI/3DfnY8LDL1dkAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD8P8HSw4EMlPZhAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDIzLTA0LTEyVDEyOjI0OjQxKzAwOjAwUmNguAAAACV0RVh0ZGF0ZTptb2RpZnkAMjAyMy0wNC0xMlQxMjoyNDo0MSswMDowMCM+2AQAAAAodEVYdGRhdGU6dGltZXN0YW1wADIwMjMtMDQtMTJUMTI6MjQ6NDErMDA6MDB0K/nbAAAAAElFTkSuQmCC" style="max-width: 100%;"></a>
<a href="https://wandb.ai" rel="nofollow"><img src="https://camo.githubusercontent.com/4ca59109e690257759530a6880b714588afc1cc7c43f085b8d83f06ce6a1177d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f77616e64622d746f6f6c732d6f72616e67653f6c6f676f3d57656967687473416e64426961736573" alt="万德宝" data-canonical-src="https://img.shields.io/badge/wandb-tools-orange?logo=WeightsAndBiases" style="max-width: 100%;"></a>
<a href="https://colab.research.google.com/drive/1wfrKqyPkz5BGD1Gkij_cvbUeweIDdRav?usp=sharing" rel="nofollow"><img src="https://camo.githubusercontent.com/7b1bb4ba8478d2054ab0acd079e69ad1ab6837cd78440b2f39cce274b1c88136/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f476f6f676c652d436f6c61622d626c75653f6c6f676f3d476f6f676c65253230436f6c6162" alt="科拉布" data-canonical-src="https://img.shields.io/badge/Google-Colab-blue?logo=Google%20Colab" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是该项目的存储库</font></font><code>Alpaca-CoT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，旨在构建一个指令微调（IFT）平台，具有广泛的指令集合（特别是CoT数据集）以及各种大型语言模型和参数高效方法的统一接口。我们不断扩大</font></font><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令调优数据收集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并集成更多的法学硕士和更高效的参数方法。此外，我们创建了一个新的分支</font></font><a href="https://github.com/PhoebusSi/Alpaca-CoT/tree/tabular_llm"><code>tabular_llm</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来构建用于解决表智能任务的表格法学硕士。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">热烈欢迎您向我们提供任何未收集的指令调优数据集（或其来源）。我们将统一格式化它们，用这些数据集训练羊驼模型（以及未来的其他法学硕士），开源</font></font><a href="https://huggingface.co/QingyiSi/Alpaca-CoT/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型检查点</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并进行广泛的实证研究。我们希望我们的项目能够为大型语言模型的开源进程做出一点微薄的贡献，降低NLP研究人员的入门门槛。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/wechat.jpg"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/wechat.jpg" width="100" height="100" align="right" style="max-width: 100%;"></a></p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
您还可以选择加入我们的群聊（微信），与更多有相同兴趣的人交流。目前群成员人数过多，无法直接通过群二维码入群。你需要先联系我才能进群。
</font></font><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息</font></font></h2><a id="user-content-news" class="anchor" aria-label="永久链接：新闻" href="#news"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠ 如果您想使用LORA之外的其他方法，请在我们的项目中安装编辑后的版本</font></font><code>pip install -e ./peft</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀12.8：LLM</font></font><code>InternLM</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被合并。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀8.16：</font></font><code>4bit quantization</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于</font></font><code>lora</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>qlora</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>adalora</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀8.16：参数有效的方法</font></font><code>Qlora</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>Sequential adapter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并被</font></font><code>Parallel adapter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">合并。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀7.24：LLM</font></font><code>ChatGLM v2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被合并。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀7.20：LLM</font></font><code>Baichuan</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被合并。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6.25：添加模型评估代码，包括belle和MMCU。</font></font></p>
</li>
</ul>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 更多的</font></font></summary>
<p dir="auto">
</p><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.20：修复模型保存中的错误并添加wandb支持。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.15：</font><font style="vertical-align: inherit;">添加更多数据集，如</font></font><code>GPT4Tools</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>Auto CoT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、 。</font></font><code>pCLUE</code><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀5.5：</font></font><a href="https://github.com/PhoebusSi/Alpaca-CoT/tree/tabular_llm"><code>tabular_llm</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个新分支来构建表格法学硕士。我们收集表格相关任务（例如表格问答）的指令微调数据，并使用它们来微调此存储库中的 LLM。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀5.4：合并了PEFT中所有参数有效的方法（例如p-tuning），可以直接通过超参数设置。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀5.4：LLM</font></font><code>MOSS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被合并。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.21：</font><font style="vertical-align: inherit;">收集数据集</font></font><code>GAOKAO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>camel</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>FLAN-Muffin</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、并格式化。</font></font><code>COIG</code><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.15：</font><font style="vertical-align: inherit;">收集数据集</font></font><code>webGPT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>dolly</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>baize</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>hh-rlhf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、并格式化。</font></font><code>OIG(part)</code><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.12：现在您可以在</font></font><a href="https://colab.research.google.com/drive/1wfrKqyPkz5BGD1Gkij_cvbUeweIDdRav?usp=sharing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Colab</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上试用 Alpaca-CoT 。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.11：</font><a href="https://github.com/paulcx"><font style="vertical-align: inherit;">@paulcx</font></a></font><code>multi-turn conversation</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加了功能</font><font style="vertical-align: inherit;">。</font></font><a href="https://github.com/paulcx"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.9：数据集</font></font><code>firefly</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>instruct</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><code>Code Alpaca</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已收集并格式化，可以</font></font><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.7：添加</font><font style="vertical-align: inherit;">了</font><font style="vertical-align: inherit;">函数</font></font><code>Parameter merging</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>Local chatting</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">@weberr </font><a href="https://github.com/weberrr"><font style="vertical-align: inherit;">。</font></a></font><code>Batch predicting</code><font style="vertical-align: inherit;"></font><code>Web service building</code><font style="vertical-align: inherit;"></font><a href="https://github.com/weberrr"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.4: 数据集</font></font><code>GPTeacher</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>Guanaco</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>HC3</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>prosocial-dialog</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、 、</font></font><code>belle-chat&amp;belle-math</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>xP3</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被</font></font><code>natural-instructions</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">收集并格式化。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.3：中国CoT数据集可以</font><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main" rel="nofollow"><font style="vertical-align: inherit;">在这里</font></a></font><code>CoT_CN_data.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到</font><font style="vertical-align: inherit;">。</font></font><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
</ul>
<p dir="auto"></p>
</details> 
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></h2><a id="user-content-overview" class="anchor" aria-label="永久链接：概述" href="#overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/platform-en.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/platform-en.png" alt="图像" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://arxiv.org/abs/2302.13971v1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [1] 是一部伟大的作品，展示了惊人的零样本和少样本能力。它显着降低了训练、微调和使用有竞争力的大语言模型的成本，即LLaMA-13B优于GPT-3(175B)，LLaMA-65B与PaLM-540B具有竞争力。最近，为了提高 LLaMA 的指令跟踪能力，</font></font><a href="https://github.com/tatsu-lab/stanford_alpaca"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stanford Alpaca [2] 在</font></font></a><font style="vertical-align: inherit;"></font><a href="https://arxiv.org/abs/2212.10560" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Self-Instruct</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [3] 技术</font><font style="vertical-align: inherit;">生成的 52K 指令跟踪数据上对 LLaMA-7B 进行了微调。</font><font style="vertical-align: inherit;">然而，目前LLM研究界仍然面临三个挑战：1.即使LLaMA-7b对计算资源仍然有很高的要求； 2. 用于指令微调的开源数据集很少； 3.缺乏对各类教学对汉语教学反应能力、CoT推理能力等模型能力影响的实证研究。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为此，我们提出了这个项目，该项目利用了随后提出的各种改进，具有以下优点：</font></font></p>
<ul dir="auto">
<li>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库包含从</font></font><a href="https://github.com/tloen/alpaca-lora"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/huggingface/peft"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">修改的代码，可以通过使用</font><a href="https://arxiv.org/pdf/2106.09685.pdf" rel="nofollow"><font style="vertical-align: inherit;">低秩适应（LoRA）</font></a><font style="vertical-align: inherit;"> [4]、</font><a href="https://github.com/huggingface/peft"><font style="vertical-align: inherit;">PEFT</font></a><font style="vertical-align: inherit;">和</font><a href="https://github.com/TimDettmers/bitsandbytes"><font style="vertical-align: inherit;">bitsandbytes</font></a></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">廉价而高效地微调 LLaMA</font></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（与斯坦福羊驼相比，性能不会下降）</font><font style="vertical-align: inherit;">。 LLaMA</font><font style="vertical-align: inherit;">模型的</font><font style="vertical-align: inherit;">、</font><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">版本可以在单个 80G A100 上轻松训练。</font></font><a href="https://arxiv.org/pdf/2106.09685.pdf" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/huggingface/peft"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/TimDettmers/bitsandbytes"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>7b</code><font style="vertical-align: inherit;"></font><code>13b</code><font style="vertical-align: inherit;"></font><code>30b</code><font style="vertical-align: inherit;"></font></li>
</ol>
</li>
<li>
<ol start="2" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本仓库中发布的模型显着</font></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高了 CoT（推理）能力</font></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ol>
</li>
<li>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本仓库中发布的模型显着</font></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高了遵循中国指令的能力</font></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ol>
</li>
<li>
<ol start="4" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该仓库包含</font></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一系列</font><font style="vertical-align: inherit;">持续收集的</font></font><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令微调数据集</font></font></a><font style="vertical-align: inherit;"></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，目前包括英文、中文和 CoT 指令。此外，还提供了使用各种指令数据集训练的检查点集合。</font></font></li>
</ol>
</li>
<li>
<ol start="5" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这个repo  </font></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成了多个LLM并统一了它们的接口</font></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可以通过超参数轻松切换。目前包括</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaMA</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ChatGLM</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [5] 、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bloom</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [6] 和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MOSS</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，未来还会继续添加更多，以便研究人员轻松调用和比较不同的 LLM。</font></font></li>
</ol>
</li>
<li>
<ol start="6" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这个repo  </font></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成了多种参数高效的方法并统一了它们的接口</font></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可以通过超参数轻松切换。目前，它包括</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LoRA</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">P-tuning</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [5] 、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">adalora</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">prefix adjustment</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，未来将继续添加更多内容，以便研究人员轻松调用和比较不同的参数高效方法。</font></font></li>
</ol>
</li>
<li>
<ol start="7" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本报告包含</font></font><strong><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">广泛的实证研究和定性分析</font></font></em></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可能会提供有价值的发现并促进未来LLM的探索。</font></font></li>
</ol>
</li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">据我们所知，这项工作是第一个研究</font><font style="vertical-align: inherit;">基于 LLaMA 和 Alpaca 的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CoT 推理的</font></font></em><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作。因此，我们将我们的工作缩写为</font></font><code>Alpaca-CoT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据采集</font></font></h2><a id="user-content-data-collection" class="anchor" aria-label="永久链接：数据收集" href="#data-collection"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">收集的数据集的相对大小可以如下图所示：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/show.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/show.png" alt="图像" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考</font></font><a href="https://github.com/yaodongC/awesome-instruction-dataset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这个</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><a href="https://github.com/yaodongC"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@yaodongC</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），我们根据以下规则标记每个收集的数据集：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（Lang）语言-标签：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EN：英文说明数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN：中文指令数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ML：[多语言]多种语言的指令数据集</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（任务）任务标签：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MT：[多任务]包含多个任务的数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS：[特定任务]针对特定任务定制的数据集</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（Gen）生成方法：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HG：[人类生成的数据集]人类创建的数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI：[自指示]使用自指示方法生成的数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MIX：[混合数据集]数据集包含人类和机器生成的数据</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COL：[数据集集合] 由其他数据集集合而成的数据集</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">统计数据</font></font></h3><a id="user-content-statistics" class="anchor" aria-label="永久链接：统计" href="#statistics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数字</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">郎</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源代码</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网址</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="https://github.com/google-research/FLAN"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">思想链</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">74771</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文/中文</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HG</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用 cot 推理进行指导</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在现有数据上注释 CoT</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/Chain-of-Thought" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/nomic-ai/gpt4all"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT4all</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">806199</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码、故事和对话</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 GPT-3.5-turbo 蒸馏</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/GPT4all" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/teknium1/GPTeacher"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GP老师</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">29013</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般、角色扮演、工具形成者</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT-4 和模具成型机</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/GPTeacher" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/JosephusCheung/GuanacoDataset" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">原驼</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">534610</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">各种语言任务</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本-&ZeroWidthSpace;&ZeroWidthSpace;达芬奇-003</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/Guanaco" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/Hello-SimpleAI/HC3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HC3</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">37175</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文/中文</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对话评价</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人类或 ChatGPT</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/HC3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/tatsu-lab/stanford_alpaca"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">羊驼毛</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52002</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般指示</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本-&ZeroWidthSpace;&ZeroWidthSpace;达芬奇-003</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/alpaca" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/allenai/natural-instructions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自然指令</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5040134</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多样化的 NLP 任务</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释数据集集合</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/Natural-Instructions" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/BelleGroup" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美女网</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1079517</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS/MT</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般、数学推理、对话</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本-&ZeroWidthSpace;&ZeroWidthSpace;达芬奇-003</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/belle_cn" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/XueFuzhao/InstructionWild"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本能狂野</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52191</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文/中文</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成、开放质量保证、头脑风暴</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本-&ZeroWidthSpace;&ZeroWidthSpace;达芬奇-003</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/instinwild" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/allenai/prosocial-dialog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">亲社会对话</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">165681</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对话</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT-3 手动重写问题+人工反馈</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/prosocial-dialog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/gbharti/finance-alpaca" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">财务_cn</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">68912</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">财务相关的质量保证</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT3.5</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/bigscience/xP3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">xP3</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">78883588</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器学习</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">涵盖 46 种语言和 16 个 NLP 任务的提示和数据集的集合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释数据集集合</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/xP3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/yangjianxin1/Firefly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">萤火虫</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1649398</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">23 个自然语言处理任务</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释数据集集合</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/firefly" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/swype/instruct" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指导</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">888969</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">增强了 GPT4All、Alpaca、开源元数据集</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 AllenAI 提供的高级 NLP 工具进行增强</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/instruct" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/sahil280114/codealpaca"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码羊驼</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">20022</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码生成、编辑、优化</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本-&ZeroWidthSpace;&ZeroWidthSpace;达芬奇-003</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/CodeAlpaca" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">羊驼_GPT4</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52002</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文/中文</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般指示</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由 GPT-4 使用 Alpaca 生成</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/alpacaGPT4" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/openai/webgpt_comparisons" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络GPT</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">18994</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">信息检索 (IR) 质量保证</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微调GPT-3，每条指令有两个输出，选择更好的一个</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/webGPT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/databrickslabs/dolly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多莉2.0</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">15015</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HG</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封闭式QA、总结等，维基百科作为参考</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/dolly" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/project-baize/baize-chatbot"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">白泽</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">653699</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Alpaca、Quora、StackOverFlow 和 MedQuAD 问题的集合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释数据集集合</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/baize" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/anthropics/hh-rlhf"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">hh-rlhf</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">284517</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对话</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人类和 RLHF 模型之间的对话</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/hh-rlhf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://laion.ai/blog/oig-dataset/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监察长办公室（部分）</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">49237</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由各种任务创建，例如问题和回答</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用数据增强、人工注释数据集收集</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/OIG" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/OpenLMLab/GAOKAO-Bench"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高考</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2785</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">考试中的多项选择题、填空题和开放式问题</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/GAOKAO" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/lightaime/camel"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">骆驼</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">760620</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工智能社会、代码、数学、物理、化学、生物学中的角色扮演对话</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT-3.5-涡轮</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/camel" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/Muennighoff/flan" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">果馅饼松饼</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1764800</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">60 个 NLP 任务</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释数据集集合</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/FLAN-Muffin" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/BAAI/COIG" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">COIG(标志指令)</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">298428</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">收集考试、翻译、人类价值调整说明和反事实纠正多轮聊天</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用自动工具和手动验证</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/COIG" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/StevenGrove/GPT4Tools"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT4工具</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">71446</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具相关说明的集合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPT-3.5-涡轮</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/gpt4tools" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/RyokoAI/ShareGPT52K" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分享聊天</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1663241</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般指示</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">众包收集人们和 ChatGPT (ShareGPT) 之间的对话</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/ShareGPT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/amazon-science/auto-cot"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动CoT</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5816</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算术、常识、符号和其他逻辑推理任务</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人工注释数据集集合</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/Auto-CoT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/OpenLMLab/MOSS"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">苔藓</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1583595</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文/中文</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SI</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般指示</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本-&ZeroWidthSpace;&ZeroWidthSpace;达芬奇-003</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/MOSS" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/thunlp/UltraChat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超级聊天</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">28247446</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"></td>
<td align="left"></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于世界的问题、写作与创作、现有材料的协助</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">两个独立的 gpt-3.5-turbo</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/ultrachat" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/Toyhom/Chinese-medical-dialogue-data"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中医</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">792099</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关医疗建议的问题</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">爬行</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/Chinese-medical" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/ydli-ai/csl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中超联赛</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">396206</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文文本生成、关键词提取、文本摘要和文本分类</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">爬行</font></font></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/CSL" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://github.com/CLUEbenchmark/pCLUE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CLUE</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1200705</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公吨</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般指示</font></font></td>
<td align="left"></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/pCLUE" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/P01son/instructions" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻评论</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">252776</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TS</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科尔</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译</font></font></td>
<td align="left"></td>
<td align="left"><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main/news_commentary" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="https://huggingface.co/datasets/lvwerra/stack-exchange-paired" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈LLaMA</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">去做</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CN</font></font></td>
<td align="left"></td>
<td align="left"></td>
<td align="left"></td>
<td align="left"></td>
<td align="left"></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></h3><a id="user-content-download" class="anchor" aria-label="永久链接： 下载" href="#download"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载所有格式化数据</font><font style="vertical-align: inherit;">。然后你应该把它们放在</font></font><a href="https://github.com/PhoebusSi/alpaca-CoT/tree/main/data"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://huggingface.co/QingyiSi/Alpaca-CoT/tree/main" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以从这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载所有经过各种类型指令数据训练的检查点</font><font style="vertical-align: inherit;">。然后，将</font></font><code>LoRA_WEIGHTS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(in )</font><font style="vertical-align: inherit;">设置为本地路径后</font></font><code>generate.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，就可以直接执行模型推理了。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据格式化</font></font></h3><a id="user-content-data-formatting" class="anchor" aria-label="永久链接：数据格式化" href="#data-formatting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们收集的所有数据都被格式化为相同的模板，其中每个样本如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>[
{"instruction": instruction string,
"input": input string, # (may be empty)
"output": output string}
]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="[
{&quot;instruction&quot;: instruction string,
&quot;input&quot;: input string, # (may be empty)
&quot;output&quot;: output string}
]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要注意的是，对于CoT数据集，我们首先使用FLAN提供的</font></font><a href="https://github.com/google-research/FLAN/blob/main/flan/v2/templates.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将原始数据集更改为各种Chain-of-Thoughts形式，然后将其转换为上述格式。可以</font></font><a href="https://github.com/PhoebusSi/alpaca-CoT/blob/main/data/origin_cot_data/formating.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到格式化脚本</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多接口统一平台</font></font></h2><a id="user-content-multi-interface-unified-platform" class="anchor" aria-label="永久链接：多接口统一平台" href="#multi-interface-unified-platform"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font></h3><a id="user-content-setup" class="anchor" aria-label="永久链接：设置" href="#setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install -r requirements.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，微调 ChatGLM 时请确保 python&gt;=3.9。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聚四氟乙烯</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想使用LORA之外的其他方法，请在我们的项目中安装编辑后的版本</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install -e ./peft
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -e ./peft" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令微调</font></font></h3><a id="user-content-instruction-finetuning" class="anchor" aria-label="永久链接：指令微调" href="#instruction-finetuning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了让研究人员对LLM进行系统的IFT研究，我们收集了不同类型的教学数据，整合了多个LLM，并统一了接口，可以轻松定制所需的搭配：</font></font></p>
<ul dir="auto">
<li><code>--model_type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：设置您要使用的LLM。目前，支持[llama、chatglm、bloom、moss]。后两者中文能力较强，未来还会整合更多的LLM。</font></font></li>
<li><code>--peft_type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：设置您要使用的 PEFT。目前支持[lora、adalora、前缀调音、p调音、提示符]。</font></font></li>
<li><code>--data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：设置IFT使用的数据类型，灵活定制所需的命令遵从能力。例如，推理能力强，设置“alpaca-cot”，中文能力强，设置“belle1.5m”，编码和故事生成能力，设置“gpt4all”，金融相关反应能力，设置“金融” 。</font></font></li>
<li><code>--model_name_or_path</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：这被设置为加载目标LLM模型权重的不同版本  </font></font><code>--model_type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。例如，要加载 llama 的 13b 版本权重，您可以设置 decapoda-research/llama-13b-hf。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单GPU</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于美洲驼</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 uniform_finetune.py --model_type llama --model_name_or_path decapoda-research/llama-7b-hf \
    --data alpaca-belle-cot --lora_target_modules q_proj v_proj \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 uniform_finetune.py --model_type llama --model_name_or_path decapoda-research/llama-7b-hf \
    --data alpaca-belle-cot --lora_target_modules q_proj v_proj \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：对于多个数据集，您可以使用</font></font><code>--data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">like</font></font><code>--data ./data/alpaca.json ./data/finance.json &lt;path2yourdata_1&gt;</code></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于聊天GLM</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 uniform_finetune.py   --model_type chatglm --model_name_or_path THUDM/chatglm-6b \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --lora_r 32 --lora_alpha 32 --lora_dropout 0.1 --per_gpu_train_batch_size 2 \
    --learning_rate 2e-5 --epochs 1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 uniform_finetune.py   --model_type chatglm --model_name_or_path THUDM/chatglm-6b \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --lora_r 32 --lora_alpha 32 --lora_dropout 0.1 --per_gpu_train_batch_size 2 \
    --learning_rate 2e-5 --epochs 1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，</font></font><code>load_in_8bit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尚不适合 ChatGLM，因此 batch_size 必须小于其他值。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为绽放</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 uniform_finetune.py   --model_type bloom --model_name_or_path bigscience/bloomz-7b1-mt \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 uniform_finetune.py   --model_type bloom --model_name_or_path bigscience/bloomz-7b1-mt \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于莫斯</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 uniform_finetune.py   ---model_type moss --model_name_or_path fnlp/moss-moon-003-sft  \
    --data alpaca --lora_target_modules q_proj v_proj --per_gpu_train_batch_size 1 \
    --learning_rate 3e-4 --epochs 3
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 uniform_finetune.py   ---model_type moss --model_name_or_path fnlp/moss-moon-003-sft  \
    --data alpaca --lora_target_modules q_proj v_proj --per_gpu_train_batch_size 1 \
    --learning_rate 3e-4 --epochs 3" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生LM</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 uniform_finetune.py   --model_type internlm --model_name_or_path internlm/internlm-7b \
    --data alpaca --lora_target_modules q_proj v_proj --lora_r 32 --lora_alpha 32 \
    --lora_dropout 0.1 --per_gpu_train_batch_size 1 --learning_rate 2e-5 --epochs 1 \
    --compute_dtype="fp32"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 uniform_finetune.py   --model_type internlm --model_name_or_path internlm/internlm-7b \
    --data alpaca --lora_target_modules q_proj v_proj --lora_r 32 --lora_alpha 32 \
    --lora_dropout 0.1 --per_gpu_train_batch_size 1 --learning_rate 2e-5 --epochs 1 \
    --compute_dtype=&quot;fp32&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，您还可以将本地路径（保存 LLM 权重的位置）传递到</font></font><code>--model_name_or_path</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.并且数据类型</font></font><code>--data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以根据您的兴趣自由设置。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多个 GPU</font></font></strong></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>torchrun --nnodes 1 --nproc_per_node <span class="pl-smi">$ngpu</span> uniform_finetune.py <span class="pl-smi">$args</span> --data <span class="pl-smi">$data</span> </pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="torchrun --nnodes 1 --nproc_per_node $ngpu uniform_finetune.py $args --data $data " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于美洲驼</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy uniform_finetune.py \
    --model_type llama --model_name_or_path decapoda-research/llama-7b-hf \
    --data alpaca-belle-cot --lora_target_modules q_proj v_proj \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy uniform_finetune.py \
    --model_type llama --model_name_or_path decapoda-research/llama-7b-hf \
    --data alpaca-belle-cot --lora_target_modules q_proj v_proj \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于聊天GLM</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy \
    uniform_finetune.py   --model_type chatglm --model_name_or_path THUDM/chatglm-6b \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --lora_r 32 --lora_alpha 32 --lora_dropout 0.1 --per_gpu_train_batch_size 2 \
    --learning_rate 2e-5 --epochs 1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy \
    uniform_finetune.py   --model_type chatglm --model_name_or_path THUDM/chatglm-6b \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --lora_r 32 --lora_alpha 32 --lora_dropout 0.1 --per_gpu_train_batch_size 2 \
    --learning_rate 2e-5 --epochs 1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，</font></font><code>load_in_8bit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尚不适合 ChatGLM，因此 batch_size 必须小于其他值。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为绽放</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy \
    uniform_finetune.py   --model_type bloom --model_name_or_path bigscience/bloomz-7b1-mt \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy \
    uniform_finetune.py   --model_type bloom --model_name_or_path bigscience/bloomz-7b1-mt \
    --data alpaca-belle-cot --lora_target_modules query_key_value \
    --per_gpu_train_batch_size 4 --learning_rate 3e-4 --epochs 1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实习生LM</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy \
    uniform_finetune.py   --model_type internlm --model_name_or_path internlm/internlm-7b \
    --data alpaca --lora_target_modules q_proj v_proj --lora_r 32 --lora_alpha 32 \
    --lora_dropout 0.1 --per_gpu_train_batch_size 1 --learning_rate 2e-5 --epochs 1 \
    --compute_dtype="fp32"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python3 -m torch.distributed.launch --nproc_per_node 4  \
    --nnodes=1 --node_rank=0 --master_addr=xxx --master_port=yyy \
    uniform_finetune.py   --model_type internlm --model_name_or_path internlm/internlm-7b \
    --data alpaca --lora_target_modules q_proj v_proj --lora_r 32 --lora_alpha 32 \
    --lora_dropout 0.1 --per_gpu_train_batch_size 1 --learning_rate 2e-5 --epochs 1 \
    --compute_dtype=&quot;fp32&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理</font></font></h3><a id="user-content-inference" class="anchor" aria-label="永久链接： 推理" href="#inference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 generate.py  --data alpaca-belle-cot --model_type llama

python3 generate.py  --data alpaca-belle-cot --model_type chatglm

python3 generate.py  --data alpaca-belle-cot --model_type bloom

</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关指令微调和推理的更多详细信息可以</font></font><a href="https://github.com/tloen/alpaca-lora"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们修改的地方找到。请注意，该文件夹</font></font><code>saved-xxx7b</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是 LoRA 权重的保存路径，LLaMA 权重是从 Hugging Face 中自动下载的。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理超参数解释</font></font></h3><a id="user-content-inference-hyper-parameter-explanation" class="anchor" aria-label="永久链接：推理超参数解释" href="#inference-hyper-parameter-explanation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>top_p=0.9,
        #Moderately increase the probability threshold of nucleus sampling to increase the quantity of candidate tokens and increase generation diversity.

temperature=1.0,
        #The previous low temperature parameter could lead to a severe polarization in the probability distribution of generated words, which degenerates the generation strategy into greedy decoding.

do_sample=True,
        #do_sample parameter is set to False by default. After setting to True, the generation methods turn into beam-search multinomial sampling decoding strategy.

no_repeat_ngram_size=6,
        #Configure the probability of the next repeating n-gram to 0, to ensure that there are no n-grams appearing twice. This setting is an empirical preliminary exploration.

repetition_penalty=1.8,
        #For words that have appeared before, in the subsequent prediction process, we reduce the probability of their reoccurrence by introducing the repetition_penalty parameter. This setting is an empirical preliminary exploration.
</code></pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数合并</font></font></h3><a id="user-content-parameter-merging" class="anchor" aria-label="永久链接：参数合并" href="#parameter-merging"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 merge.py --model_type llama --size 7b --lora_dir xxx --merged_dir yyy
</code></pre><div class="zeroclipboard-container">
   
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地聊天</font></font></h3><a id="user-content-local-chatting" class="anchor" aria-label="永久链接：本地聊天" href="#local-chatting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 server.py --model_type chatglm --size 6b --lora_dir xxx
</code></pre><div class="zeroclipboard-container">
  
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络服务建设</font></font></h3><a id="user-content-web-service-building" class="anchor" aria-label="永久链接：Web服务构建" href="#web-service-building"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python3 web.py --model_type chatglm --size 6b --lora_dir xxx
</code></pre><div class="zeroclipboard-container">
  
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文开放法学硕士教学调整的实证研究（截至6月25日）</font></font></h2><a id="user-content-empirical-study-of-instruction-tuning-open-llms-in-chinese-as-of-june-25th" class="anchor" aria-label="永久链接：中文开放法学硕士指令调整的实证研究（截至 6 月 25 日）" href="#empirical-study-of-instruction-tuning-open-llms-in-chinese-as-of-june-25th"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注：以下实验结果均来自___中文大语言模型指令调优的实证研究___。</font></font></summary>
<p dir="auto">
</p><div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. 基准</font></font></h3><a id="user-content-1-benchmarks" class="anchor" aria-label="永久链接：1. 基准" href="#1-benchmarks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本文选取Belle-eval和MMCU两个评价基准对中文LLM能力进行综合评价。</font></font></p>
<p dir="auto">Belle-eval is constructed by self-instruct with ChatGPT, which has 1,000 diverse instructions that involve 10 categories covering common NLP tasks (e.g., QA) and challenging tasks (e.g., code and math). We use ChatGPT to rate the model responses based on the golden answers. This benchmark is considered to be as the assessment of AGI (instruction-following) capability.</p>
<p dir="auto">MMCU is a collection of Chinese multiple choice questions in four professional disciplines of medicine, law, psychology and education (e.g., Gaokao examination). It allows LLMs to take exams in human society in a multiple-choice test manner, making it suitable for evaluating the breadth and depth of knowledge of LLMs across multiple disciplines.</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-benchmarks.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-benchmarks.png" width="35%" style="max-width: 100%;"></a>
</p>
<p dir="auto">Data statistics of Belle-eval and MMCU are shown in the table above.</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">2. Main Factors</h3><a id="user-content-2-main-factors" class="anchor" aria-label="Permalink: 2. Main Factors" href="#2-main-factors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">We conduct experiments to study the three main factors in instruction-tuning LLMs: LLM bases, Parameter-efficient Methods, Chinese Instruction Datasets.</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">2.1 LLM Bases</h4><a id="user-content-21-llm-bases" class="anchor" aria-label="Permalink: 2.1 LLM Bases" href="#21-llm-bases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">For open LLMs, we test existing LLMs and LLMs fine-tuned with LoRA on Alpaca-GPT4 on Belle-eval and MMCU, respectively.</p>
   <p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-llms1.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-llms1.png" width="80%" style="max-width: 100%;"></a>
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-llms2.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-llms2.png" width="40%" style="max-width: 100%;"></a>
</p>
<p dir="auto">Table 2 shows the scores of open LLMs on Belle-eval. Table 3 shows the accuracy of LLMs on MMCU. They fine-tune all the open LLMs with the same parameter-efficient method LoRA and the same instruction dataset Alpaca-GPT4.</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em></p>
<ol dir="auto">
<li>
<p dir="auto">Evaluation of Existing LLMs</p>
<p dir="auto"><em><strong>Performance on Belle-eval</strong></em></p>
<p dir="auto">(1) For base LLMs, Bloom performs the best.</p>
<p dir="auto">(2) For sft LLMs, ChatGLM outperforms others by large margins, thanks to the fact that it is trained with the most Chinese tokens and HFRL.</p>
<p dir="auto">(3) The Open QA, Math, CloseQA and Extract categories are still very challenging for existing open LLMs.</p>
<p dir="auto">(4) Vicuna and moss-sft have clear improvements compared to their bases, LLaMA and moss-base, respectively.</p>
<p dir="auto">(5) In contrast, the performance of sft models, Bloomz and Bloomz-mt, is reduced compared to the base model Bloom, because they tend to generate a shorter response.</p>
<p dir="auto"><em><strong>Performance on MMCU</strong></em></p>
<p dir="auto">(1) All base LLMs perform poorly because it is almost difficult to generate content in the specified format before fine-tuning, e.g., outputting option numbers.</p>
<p dir="auto">(2) All sft LLMs outperform their corresponding base LLMs, respectively. In particular, Bloomz performs the best (even beats ChatGLM) because it can generate option number directly as required without generating other irrelevant content, which is also due to the data characteristics of its supervised fine-tuning dataset xP3.</p>
<p dir="auto">(3) Among the four disciplines, law is the most challenging for LLMs.</p>
<p align="center" dir="auto">
 <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-llms3.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-llms3.png" width="40%" style="max-width: 100%;"></a>
</p></li>
</ol>
<p dir="auto"></p>
<p dir="auto">The performance results of LLMs after instruction-tuning on Alpaca-GPT4-zh are shown in Figure 1.</p>
<ol start="2" dir="auto">
<li>
<p dir="auto">Instruction-tuning Different LLMs</p>
<p dir="auto">(1) On Belle-eval, the performance improvement of sft LLMs brought by instruction-tuning is not as significant as that of base LLMs, except for sft Bloomz and Bloomz-mt.</p>
<p dir="auto">(2) Vicuna and ChatGLM encounter performance drops after instruction-tuning, because Vicuna is trained from real human-ChatGPT conversations, with better quality than Alpaca-GPT4. ChatGLM adopts HFRL, which may be no longer suitable for further instruction-tuning.</p>
<p dir="auto">(3) On MMCU, most LLMs achieve performance boosts after instruction-tuning, with the exception of Bloomz and Bloomz-mt, which have unexpectedly significantly decreased performance.</p>
<p dir="auto">(4) After instruction-tuning, Bloom has significant improvements and performs well on both benchmarks. Although ChatGLM beats Bloom consistently, it suffers performance drop during instruction-tuning. Therefore, among all open LLMs, Bloom is most suitable as a foundation model in the subsequent experiments for Chinese instruction-tuning exploration.</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">2.2 Parameter-efficient Methods</h4><a id="user-content-22-parameter-efficient-methods" class="anchor" aria-label="Permalink: 2.2 Parameter-efficient Methods" href="#22-parameter-efficient-methods"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">For parameter-efficient methods other than LoRA, the paper collects a range of parameter-efficient methods to instruction-tune Bloom on the Alpaca-GPT4 dataset.</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-para1.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-para1.png" width="40%" style="max-width: 100%;"></a>
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-para2.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-para2.png" width="40%" style="max-width: 100%;"></a>
</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em></p>
<ol dir="auto">
<li>
<p dir="auto">Comparison of Parameter-efficient Methods</p>
<p dir="auto">(1) SadapterH performs the best among all parameter-efficient methods, which can be used as an alternative to LoRA.</p>
<p dir="auto">(2) P-tuning and prompt-tuning underperform others by large margins, indicating that only adding trainable layers in the embedding layer are not enough to support LLMs for generation tasks.</p>
<p dir="auto">(3) Although AdaLoRA is an improvement of LoRA, its performance has a clear drop, possibly because the LoRA's trainable parameters for LLMs are not suitable for further reduction.</p>
<p dir="auto">(4) Comparing the upper and lower parts, it can be seen that increasing the number of trainable parameters for sequential adapters (i.e., SadapterP and SadapterH) does not bring gain, while the opposite phenomenon is observed for parallel adapters(i.e., P-adapter)</p>
</li>
<li>
<p dir="auto">Training Loss</p>
<p dir="auto">(1) Prompt-tuning and P-tuning converge the slowest and has the highest losses after convergence. This shows that embedding-only adapters are not suitable for instruction-tuning LLMs.</p>
<p dir="auto">(2) The initial loss of AdaLoRA is very high because it requires simultaneous learning of parameter budget allocation, which makes the model unable to fit the training data well.</p>
<p dir="auto">(3) The other methods can quickly converge on training data and fit it well.</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">2.3 Chinese instruction Datasets</h4><a id="user-content-23-chinese-instruction-datasets" class="anchor" aria-label="Permalink: 2.3 Chinese instruction Datasets" href="#23-chinese-instruction-datasets"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">For the impact of various types of Chinese instruction datasets, authors gather popular open Chinese instructions (as shown in Table 5) to fine-tune Bloom with LoRA.</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-data1.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-data1.png" width="80%" style="max-width: 100%;"></a>
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-data2.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-data2.png" width="80%" style="max-width: 100%;"></a>
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-data3.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-data3.png" width="40%" style="max-width: 100%;"></a>
</p>
<p dir="auto">Table 6 and Table 7 show Bloom's fine-tuning on different instruction datasets.</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em></p>
<ol dir="auto">
<li>
<p dir="auto">Performance on Belle-eval</p>
<p dir="auto">(1) the instruction data constructed by ChatGPT (e.g., using self-instruction methods or collecting real human-ChatGPT conversations) consistently enhances the instruction-following ability with 3.1 ∼ 11-point score increases.</p>
<p dir="auto">(2) Among these datasets, Belle has the best performance due to the largest amount of instruction data. However, the performance of models trained on moss-sft-data, containing more data built in a similar way, is unsatisfactory.</p>
<p dir="auto">(3) The performance brought by the Alpaca-GPT4 instructions is the second best, with only 49K being comparable to the 1.54M Belle.</p>
<p dir="auto">(4) Instinwild brings the least performance gains among them because the seed instructions it crawls from Tweet ("in wild") are not as comprehensive as those (like Alpaca) carefully designed by humans.</p>
<p dir="auto">(5) These ChatGPT-based data mainly have a significant improvement effect on open generation tasks such as Brain Storm and Generation, while there is a significant decrease in tasks that require high reading comprehension skills, such as Close QA and Extract.</p>
<p dir="auto">(6) These instruction datasets cause damage to the model's instruction-following ability, because the form and intent of each NLP or examination dataset are unitary, which can easily be overfitted.</p>
<p dir="auto">(7) Among them, COIG-trans performs the best because it involves over 2000 different tasks with a wide variety of task instructions. In contrast, xP3 and COIG-ccmc have the worst negative impact on model performance. Both of them only cover a few types of tasks (translation and QA for the former, counterfactual correction conversations for the latter), which hardly cover the popular instructions and tasks for humans.</p>
</li>
<li>
<p dir="auto">Performance on MMCU</p>
<p dir="auto">(1) Instruction-tuning on each dataset can always result in performance improvement.</p>
<p dir="auto">(2) Among the ChatGPT-based data shown in the upper part, ShareGPT-zh underperforms others by large margins. This may be due to the fact that real users rarely ask multiple choice questions about academic topics.</p>
<p dir="auto">(3) Among the dataset-collection data shown in the lower part, HC3 and COIG-ccmc results in the lowest accuracy because the unique questions of HC3 are only 13K, and the task format of COIG-ccmc is significantly different from MMCU.</p>
<p dir="auto">(4) COIG-exam brings the greatest accuracy improvement, benefiting from the similar task format as MMCU.</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">3. Other Factors</h3><a id="user-content-3-other-factors" class="anchor" aria-label="Permalink: 3. Other Factors" href="#3-other-factors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Four Other Factors: CoT, Expansion of Chinese Vocabulary, Language of Prompts and Human-value Alignment</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">3.1 CoT</h4><a id="user-content-31-cot" class="anchor" aria-label="Permalink: 3.1 CoT" href="#31-cot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">For CoT, authors compare the performance before and after adding CoT data during instruction-tuning.</p>
<p dir="auto"><em><strong>Experiment Settings:</strong></em></p>
<p dir="auto">We collect 9 CoT datasets and their prompts from FLAN, and then translate them into Chinese using Google Translate. They compare the performance before and after adding CoT data during instruction-tuning.</p>
<p dir="auto">First note the way to add CoT data as "Alpaca-GPT4+CoT". In addition, add a sentence "先思考，再决定" ("think step by step" in Chinese) at the end of each instruction, to induce the model to respond to instructions based on the CoT, and label this way as "Alpaca-GPT4+CoT*".</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-cot.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-cot.png" width="40%" style="max-width: 100%;"></a>
</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em></p>
<ol dir="auto">
<li>
<p dir="auto">"Alpaca-GPT4+CoT" outperforms "Alpaca-GPT4" in Code and Math tasks that require strong reasoning ability. Besides, there is also a significant improvement in the MMCU Education task.</p>
</li>
<li>
<p dir="auto">As shown in the line of "Alpaca-GPT4+CoT*", the simple sentence can further improve the performance of reasoning tasks Code and Education, while the Math performance is slightly inferior to "Alpaca-GPT4+CoT". This may require further exploring of more robust prompts.</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">3.2 Expansion of Chinese Vocabulary</h4><a id="user-content-32-expansion-of-chinese-vocabulary" class="anchor" aria-label="Permalink: 3.2 Expansion of Chinese Vocabulary" href="#32-expansion-of-chinese-vocabulary"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">For expansion of Chinese vocabulary, authors test the influence of the number of Chinese tokens in the tokenizer’s vocabulary on LLMs’ ability to express Chinese. For example, if a Chinese character is in the vocabulary, it can be represented by a single token, otherwise it may require multiple tokens to represent it.</p>
<p dir="auto"><em><strong>Experiment Settings:</strong></em> Authors mainly conduct experiments on LLaMA, which uses SentencePiece(32K vocabulary size of Chinese characters) covering fewer Chinese characters than Bloom(250K).</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-voc.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-voc.png" width="45%" style="max-width: 100%;"></a>
</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em></p>
<ol dir="auto">
<li>
<p dir="auto">Pre-training on more Chinese corpus with expansion of Chinese vocabulary is consistently helpful for instruction-following ability.</p>
</li>
<li>
<p dir="auto">And counterintuitively, "llama-voc-pre-l" (100B) is inferior to "llama-voc-pre" (20B) on MMCU, which shows that pre-training on more data may not necessarily lead to higher performance for academic exams.</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">3.3 Language of Prompts</h4><a id="user-content-33-language-of-prompts" class="anchor" aria-label="Permalink: 3.3 Language of Prompts" href="#33-language-of-prompts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">For the language of prompts, authors test the suitability of instruction fine-tuning for using Chinese prompts.</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-lan.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-lan.png" width="60%" style="max-width: 100%;"></a>
</p>
<p dir="auto">Figure 4 shows the results of using Chinese and English prompts based on LLaMA and Bloom.  When instruction-tuning LLaMA, using Chinese prompts can improve the performance on both benchmarks compared to English prompts, while the opposite phenomenon can be observed on Bloom.</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em></p>
<ol dir="auto">
<li>
<p dir="auto">For models with weaker Chinese abilities(e.g., LLaMA), using Chinese prompts can effectively help respond in Chinese.</p>
</li>
<li>
<p dir="auto">For models with good Chinese abilities (e.g., Bloom), using prompts in English (the language they are better at) can better guide the model to understand the process of fine-tuning with instructions.</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">3.4 Human-value Alignment</h4><a id="user-content-34-human-value-alignment" class="anchor" aria-label="Permalink: 3.4 Human-value Alignment" href="#34-human-value-alignment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">To avoid LLMs generating toxic content, aligning them with human values is a crucial issue. We add human-value alignment data built by COIG into instruction-tuning to explore its impact.</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/chinesellms-human.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/chinesellms-human.png" width="30%" style="max-width: 100%;"></a>
</p>
<p dir="auto">Figure 5 compares the results of instruction-tuning with and without human-value alignment.</p>
<p dir="auto"><em><strong>Experimental Results:</strong></em> The human-value alignment results in a slight performance drop. How to balance the harmlessness and performance of LLMs is a research direction worth exploring in the future.</p>
<p dir="auto"></p>
</details> 
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定量分析</font></font></h2><a id="user-content-quantitative-analysis" class="anchor" aria-label="固定链接：定量分析" href="#quantitative-analysis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注：下图为截至3月26日采集数据集的统计数据，仅作为数据采集动机展示。已经收集了更多的数据集，例如金融相关的指令数据集。</font></font></summary>
<p dir="auto">
</p><p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/piechart.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/piechart.png" alt="data collection statistics" style="max-width: 100%;"></a>
The current collection of instruction-finetuning datasets consists mainly of three parts:</p>
<ul dir="auto">
<li><code>alpaca_data_cleaned.json</code>: about 52K English instruction-following training samples.</li>
<li><code>CoT_data.json</code>: 9 CoT datasets involving about 75k samples. (published by FLAN[7])</li>
<li><code>belle_data_cn.json</code>:  about 0.5M Chinese |instruction-following training samples. (published by BELLE [8])</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Ablation of CoT and Chinese Instructions</h3><a id="user-content-ablation-of-cot-and-chinese-instructions" class="anchor" aria-label="Permalink: Ablation of CoT and Chinese Instructions" href="#ablation-of-cot-and-chinese-instructions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/ablation-cot.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/ablation-cot.png" alt="ablation-cot" style="max-width: 100%;"></a>
"w/o CoT" and "w/o CN" denote models that exclude CoT data and Chinese instructions from their instruction finetuning data, respectively.</p>
<p dir="auto">The above table shows two examples (involving with numerical calculations) that require a certain amount of reasoning ability to respond correctly.
As shown in the middle column, <code>Ours w/o CoT</code> fails to generate the correct response, which shows that once the finetuning data does not contain CoT data, the model's reasoning ability significantly decreases. This further demonstrates that CoT data is essential for LLM models.</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/ablation-cn.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/ablation-cn.png" alt="ablation-cot" style="max-width: 100%;"></a></p>
<p dir="auto">The above table shows two examples that require the ability to respond to Chinese instructions.
As shown in the right column, either the generated content of <code>Ours w/o CN</code> is unreasonable, or the Chinese instructions are answered in English by <code>Ours w/o CN</code>. This shows that removing Chinese data during finetuning will cause the model to be unable to handle Chinese instructions, and further demonstrates the need to collect Chinese instruction finetuning data.</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/ablation-both.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/ablation-both.png" alt="ablation-cot" style="max-width: 100%;"></a></p>
<p dir="auto">The above table shows a relatively difficult example, which requires both a certain accumulation of knowledge of Chinese history and a logical and complete ability to state historical events. As shown in this table, <code>Ours w/o CN</code> can only generate a short and erroneous response, because due to the lack of Chinese finetuning data, the corresponding knowledge of Chinese history is naturally lacking.  Although <code>Ours w/o CoT</code> lists some relevant Chinese historical events, its logic of expression is self-contradictory, which is caused by the lack of CoT data.
`</p>
<p dir="auto"><strong>In summary, the models finetuned from our complete dataset (English, Chinese, and CoT instruction data) can significantly improve model reasoning and Chinese instruction following abilities.</strong></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">The Effect of CoT Data</h3><a id="user-content-the-effect-of-cot-data" class="anchor" aria-label="Permalink: The Effect of CoT Data" href="#the-effect-of-cot-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/CoT-comparison.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/CoT-comparison.png" alt="CoT-comparison" style="max-width: 100%;"></a>
Samples of each odd number of rows do not apply the CoT prompt, such as "step-by-step reasoning." Both <code>Ours(w/CoT)</code> and Alpaca are based on LLaMA-7B, and the only difference between them two is that the instruction-finetuning data of <code>Ours(w/CoT)</code> has a extra CoT data than that of Alpaca.</p>
<p dir="auto">From the above table, we find that:</p>
<ul dir="auto">
<li><code>Ours(w/CoT)</code> always generates the correct rationale before the answer, while Alpaca fails to generate any reasonable rationale, as shown in the first 4 examples (commonsense questions). This shows that using CoT data for finetuning can significantly improve reasoning ability.</li>
<li>For <code>Ours(w/CoT)</code>, the CoT prompt (e.g., concatenate 'step-by-step' with the input question) has little effect on easy examples (e.g., commonsense questions) and has an important effect on challenging questions (e.g., questions requiring reasoning, like the last four examples).</li>
<li>For Alpaca, CoT prompt always has little effect or even negative impact. For the last two examples, after adding CoT prompt, Aplpaca changes the correct generated answer to the wrong one. This may be due to the inconsistency between the input forms of finetuning and inference.</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">The Effect of Chinese Instruction Data</h3><a id="user-content-the-effect-of-chinese-instruction-data" class="anchor" aria-label="Permalink: The Effect of Chinese Instruction Data" href="#the-effect-of-chinese-instruction-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><em>Quantitative comparison of responses to Chinese instructions.</em>
<a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/CN-compareCN.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/CN-compareCN.png" alt="CN_compare_CN" style="max-width: 100%;"></a></p>
<p dir="auto">Our model is finetuned from a 7B LLaMA on 52K English instructions and 0.5M Chinese instructions. Stanford Alpaca (our reimplementation) is finetuned from a 7B LLaMA on 52K English instructions. BELLE is finetuned from a 7B BLOOM on 2B Chinese instructions.</p>
<p dir="auto">From the above table, several observations can be found:</p>
<ul dir="auto">
<li>Compared to Alpaca, <code>ours (w/ CN)</code> has a stronger ability to understand Chinese instructions. For the first example, Alpaca fails to distinguish between the <code>instruction</code> part and <code>input</code> part, while we do.</li>
<li>Chinese instruction finetuning data can significant enhance the ability to interact in Chinese. For the second example, <code>ours (w/ CN)</code> not only provides the correct code, but also provides the corresponding Chinese annotation, while Alpaca does not. In addition, as shown in the 3-5 examples, Alpaca can only respond to Chinese instruction with an English response.</li>
<li>Compared to BELLE, <code>ours (w/ CN)</code>'s performance on instructions requiring an open response (as shown in last two examples) still needs to be improved. BELLE's outstanding performance against such instructions is due to: 1. Its BLOOM backbone model encounters much more multilingual data during pre-training; 2. Its Chinese instruction finetuning data is more than ours, that is, 2M vs 0.5M.</li>
</ul>
<p dir="auto"><em>Quantitative comparison of responses to English instructions. The purpose of this subsection is to explore whether finetuning on Chinese instructions has a negative impact on Alpaca.</em>
<a target="_blank" rel="noopener noreferrer" href="/PhoebusSi/Alpaca-CoT/blob/main/figures/CN_compareEN.png"><img src="/PhoebusSi/Alpaca-CoT/raw/main/figures/CN_compareEN.png" alt="CN_compare_EN" style="max-width: 100%;"></a></p>
<p dir="auto">From the above table, we find that:</p>
<ul dir="auto">
<li>Finetuning with Chinese instruction data does not weaken the original English instruction–following ability, on the contrary, there is also a certain enhancement in generating a better response to English instructions. The response of <code>ours (w/ CN)</code> shows more detail than that of Alpaca, e.g. for the third example, <code>ours (w/ CN)</code> list three more provinces than Alpaca.</li>
</ul>
<p dir="auto"></p>
</details> 
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用此存储库中的数据收集、代码和实验结果，请引用该存储库。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@misc{si2023empirical,
      title={An Empirical Study of Instruction-tuning Large Language Models in Chinese}, 
      author={Qingyi Si and Tong Wang and Zheng Lin and Xu Zhang and Yanan Cao and Weiping Wang},
      year={2023},
      eprint={2310.07328},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
</code></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于数据和模型，请注明原始数据、参数有效方法和法学硕士来源。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们要特别感谢 APUS AilMe Lab 赞助 8 个 A100 GPU 进行实验。</font></font></p>
<p align="right" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><a href="#top"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回到顶部</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢我们的贡献者</font></font></h2><a id="user-content-all-thanks-to-our-contributors" class="anchor" aria-label="永久链接：感谢我们的贡献者" href="#all-thanks-to-our-contributors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<a href="https://github.com/PhoebusSi/Alpaca-CoT/graphs/contributors">
  <img src="https://camo.githubusercontent.com/d8422a652015c91da3a5f1db84c3b9696d589ed085de1fda49818e6d333ddc60/68747470733a2f2f636f6e747269622e726f636b732f696d6167653f7265706f3d50686f6562757353692f416c706163612d436f54" data-canonical-src="https://contrib.rocks/image?repo=PhoebusSi/Alpaca-CoT" style="max-width: 100%;">
</a>
</article></div>
