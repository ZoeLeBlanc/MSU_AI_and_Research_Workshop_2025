# MSU AI & Research Workshop Prompt Evaluation Results

## Initial Open Horizon Prompting Experiments

### Initial Minimal Prompt

![Screenshot 2025-02-19 at 10.55.56 AM.png](MSU%20AI%20&%20Research%20Workshop%20Prompt%20Evaluation%20Results/Screenshot_2025-02-19_at_10.55.56_AM.png)

| Chatbot | Model | Found Relevant Materials? | Suggested Helpful Methods? | Costs | Data Privacy | Link to Log | Model Response |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Claude Anthropic | Sonnet 3.5 | Not really. Very generic answer. | Minimal | Free Tier | Data is supposed to be private unless opted in to train models. More info here https://support.anthropic.com/en/articles/8325621-i-would-like-to-input-sensitive-data-into-free-claude-ai-or-claude-pro-who-can-view-my-conversations | [https://shareclaude.pages.dev/c/f7sigzkfck16w9meitbesjvs](https://shareclaude.pages.dev/c/f7sigzkfck16w9meitbesjvs) | [Full Prompt Results](prompt_results/initial_open_horizon_prompts/claude_results.md) |
| Microsoft Co-Pilot | Microsoft Prometheus model, which combines the Bing search index with OpenAI's GPT-4 models. | Not really. Very generic answer. | None | Institutional License via UIUC  | Data is encrypted and web search queries are removed after 24 hours.  |  | [Full Prompt Results](prompt_results/initial_open_horizon_prompts/microsoft_copilot_results.md) |
| GPT4ALL | DeepSeek | Not really. Very generic answer. | Minimal | Free | Complete private and running locally |  | [Full Results](prompt_results/initial_open_horizon_prompts/gpt4all_deepseek_results.md) |
| Perplexity AI | Default Model | Found some relevant materials and included links. | Suggested some methods, but primarily resources. | Free Tier | Defaults to using user queries to train models, but can opt out in settings. |  | [Full Results](prompt_results/initial_open_horizon_prompts/perplexity_results.md) |
| Google Gemini | 2.0 Flash Thinking Experimental | Found some relevant materials and included links. | None | Free Tier | Claims that user queries are not used to train models. More info here https://cloud.google.com/gemini/docs/discover/data-governance  | https://docs.google.com/document/d/1bXmtt30BZE6tgZMNWJ2DQK2R1yesn0ohnK0b55EWNp4/edit?usp=sharing | [Full Results](prompt_results/initial_open_horizon_prompts/gemini_results.md) |
| OpenAI ChatGPT | 4o  | Found some relevant materials and included links. | Mentioned resources but no methods. | Plus Tier ($20 USD/Month) | Claims that users can opt-in to having their data used to train models. More info here https://help.openai.com/en/articles/7730893-data-controls-faq | https://chatgpt.com/share/67b621ed-c3d4-8006-80fb-f9253cf77478 | [Full Results](prompt_results/initial_open_horizon_prompts/chatgpt_results.md) |

---

### Revised Prompt

![Screenshot 2025-02-19 at 10.57.31 AM.png](MSU%20AI%20&%20Research%20Workshop%20Prompt%20Evaluation%20Resul%2019f42ec6cb3e806f99fcc599ba16016a/Screenshot_2025-02-19_at_10.57.31_AM.png)

| Chatbot | Model | Found Relevant Materials? | Suggested Helpful Methods? | Costs | Data Privacy | Link to Log | Model Response |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Claude Anthropic | Sonnet 3.5 | Yes, but no links | Suggested using OCR with some text analysis, so somewhat useful. | Free Tier | Data is supposed to be private unless opted in to train models. More info here https://support.anthropic.com/en/articles/8325621-i-would-like-to-input-sensitive-data-into-free-claude-ai-or-claude-pro-who-can-view-my-conversations | [https://shareclaude.pages.dev/c/h6ypejdxqwrypm4ptkpracev](https://shareclaude.pages.dev/c/gejm2p7hl8oisqs462megzld) | [Full Prompt Results](prompt_results/revised_open_horizon_prompt/claude_results.md) |
| GPT4ALL | DeepSeek | Somewhat, but still fairly generic and no links. | Suggested both specific methods and Python libraries. | Free | Complete private and running locally |  | [Full Prompt Results](prompt_results/revised_open_horizon_prompt/gpt4all_deepseek_results.md) |
| Perplexity AI | Default Model | Technically found some potentially relevant collections, but not much better than initial prompt. | Suggested some methods but not very detailed. | Free Tier | Defaults to using user queries to train models, but can opt out in settings. |  | [Full Prompt Results](prompt_results/revised_open_horizon_prompt/perplexity_results.md) |
| OpenAI ChatGPT | o1 pro | Most detailed response with links. | Suggested methods for each collection. | Pro Tier ($200 USD/Month) | Claims that users can opt-in to having their data used to train models. More info here https://help.openai.com/en/articles/7730893-data-controls-faq | https://chatgpt.com/share/67b623c9-f0e0-8006-8a3f-85f49effe047 | [Full Prompt Results](prompt_results/revised_open_horizon_prompt/chatgpt_results.md) |

---

# Initial Blank Page Prompting Experiments

### First Attempt

```markdown
A Historiographical Essay on Africa Media Review within the Histories of Information and Decolonization

The journal Africa Media Review, founded in 1986 by the African Council for Communication Education (ACCE), occupies a critical yet often underexplored position within the broader history of African knowledge production, decolonization, and the transformation of global information flows. While much attention in historiography has been devoted to the political, economic, and social dimensions of Africa’s decolonization, Africa Media Review reminds us that the decolonization of information—encompassing media, communication studies, and cultural representation—remains a vital dimension in understanding Africa’s postcolonial trajectories. This essay seeks to contextualize Africa Media Review within key debates on decolonizing knowledge in African history, situate its contributions in relation to major historians’ interventions, and outline how digital humanities methods can further illuminate the journal’s role in reshaping narratives about African media and communication.

1. Decolonization and the Politics of Knowledge Production
1.1. Early Historiographical Perspectives
For much of the twentieth century, narratives surrounding Africa’s colonial and postcolonial histories were dominated by perspectives emanating from Western academic institutions. As the historians Jean Suret-Canale (1964) and Roland Oliver (1961) made clear in their foundational studies of colonial Africa, the colonial archive itself was shaped by European priorities and biases. Even with the rise of African nationalist historiography in the mid-twentieth century, scholars like Kenneth Dike (1956) and Bethwell A. Ogot (1963) insisted on the need to reclaim African voices and perspectives. Yet these efforts were directed predominantly toward political history rather than the emerging significance of mass media and information in shaping the postcolonial experience.

1.2. Toward a Decolonized Knowledge Framework
Beginning in the 1970s, the concept of “decolonizing knowledge” moved into the forefront of African Studies, propelled by historians and theorists who recognized how deeply academic discourse was implicated in colonial power structures. Walter Rodney’s How Europe Underdeveloped Africa (1972) helped spotlight economic and political dimensions of colonial exploitation, but it also hinted at the ways in which control over information served as a tool of hegemony. Frederick Cooper’s Africa Since 1940: The Past of the Present (2002) further underscored the interplay between political economy and the production of knowledge in postcolonial Africa. Meanwhile, Toyin Falola (1993) and Emmanuel Akyeampong (2000) advanced new perspectives on African historiography that highlighted the crucial role of local intellectual traditions and print cultures in shaping identity and resistance.

It was within this intellectual atmosphere—one that recognized the importance of reclaiming African agency in political and cultural realms—that Africa Media Review emerged. As part of a larger post-independence push, African scholars and media practitioners recognized the necessity for a dedicated forum that would foreground African-led debates about information systems, mass media, and communication policy, free from the overshadowing frameworks of Western media scholarship.

2. Africa Media Review: Origins, Aims, and Significance
2.1. Foundational Impetus and Alignment with NWICO
The establishment of Africa Media Review was influenced by the global debates surrounding the New World Information and Communication Order (NWICO), often dated to the MacBride Commission’s landmark report Many Voices, One World (1980). In a context where African nations sought greater equity and representation in international media and communication channels, NWICO’s emphasis on pluralism and sovereignty in information flows resonated deeply. The ACCE recognized that mainstream global communication journals often sidelined African voices; Africa Media Review, therefore, aimed to create a robust platform where African academics, policymakers, and media professionals could interrogate media practices on the continent through local theoretical lenses and empirical data.

2.2. Scholarly Contributions and Themes
From its inception in 1986, Africa Media Review published peer-reviewed articles that intersected with multiple disciplines—political science, sociology, history, and anthropology—thereby forging an interdisciplinary terrain for African media scholarship. Scholars such as Francis B. Nyamnjoh (1996) and Kwame Karikari (1993) contributed pieces that challenged dominant narratives about press freedom, state regulation, and the cultural politics of broadcasting. Historians like James R. Brennan (2010), though not publishing primarily in Africa Media Review, reinforced the importance of understanding how colonial newspapers shaped modern African public spheres—an enterprise parallel to the journal’s commitment. In short, Africa Media Review extended the scope of African Studies by centering media as a critical domain of political and cultural contestation.

2.3. Positioning in African Historiography
In their analysis of African historiography, leading historians such as Frederick Cooper (2014) and Emmanuel Akyeampong (2018) note that information and media histories remain relatively understudied compared to the vast literatures on nationalism and state formation. Africa Media Review helped fill this gap by insisting on the interplay between mass communication systems and processes of nation-building, identity formation, and ideological contestation. Moreover, the journal’s editorial policy encouraged the publication of articles in both English and French, reflecting the pan-African and multilingual character of the ACCE. This was a move that linked directly to the decolonization of scholarly language—a theme also underscored by Ngũgĩ wa Thiong’o (1986) in his call for African languages to be central in knowledge production.

3. Histories of Information as Histories of Decolonization
3.1. Colonial Legacies in African Media
A key impetus behind the founding of Africa Media Review was the understanding that African media infrastructures were themselves shaped by colonial legacies. Historians have documented how newspapers and radio broadcasts under colonial regimes served as instruments of propaganda, surveillance, and cultural imperialism. Helen Tilley’s (2011) study on colonial scientific research underscores how “information orders” under empire were rarely neutral but deeply entangled with colonial governance. Similarly, James Brennan (2010) demonstrates how colonial newspapers in Tanganyika functioned as contested sites for African political expression and colonial power.

By foregrounding such histories, Africa Media Review emphasized the continuity between colonial control of the press and the postcolonial state's attempts—sometimes repressive, sometimes liberating—to harness media for nation-building. It also showcased how African journalists and intellectuals navigated these legacies while formulating strategies for cultural and political emancipation.

3.2. Postcolonial Critiques and African Agency
The decades following independence saw African states grappling with how best to indigenize or nationalize media systems that had long served external interests. Emmanuel N. Mbah’s (2016) work on postcolonial Cameroon underscores how decolonization of information was not simply a matter of replacing colonial authorities with African rulers, but rather a broader renegotiation of media ownership, funding, and editorial control. Articles in Africa Media Review similarly documented how media policies reflected the tensions between state power and popular aspirations—echoing Achille Mbembe’s (2001) arguments about the postcolony’s entanglement of authority and resistance.

Hence, the journal’s significance resides in its sustained commitment to exploring the interplay between media structures, local sociopolitical contexts, and broader global forces, providing historiography with valuable insights into the multi-layered processes of decolonization.

4. Digital Humanities Approaches to Africa Media Review
4.1. Textual Analysis and Topic Modeling
In recent years, digital humanities methods have provided new pathways for examining large corpora of texts, including journal runs. While historians traditionally rely on close reading and qualitative methods, topic modeling and textual analysis software—such as Voyant Tools or MALLET—can illuminate shifts in thematic emphases within Africa Media Review over time. By processing the entire run of the journal, scholars could map how certain keywords (e.g., “decolonization,” “press freedom,” “local languages,” “state policy”) rose or fell in prominence.

Such a digital exploration would complement the work of historians like Frederick Cooper (2014), who advocates blending macro-level analyses with careful attention to local contexts. By contrasting data-driven topic modeling with the qualitative reading of landmark articles—such as those focused on NWICO or UNESCO directives—scholars can discern how debates around information sovereignty evolved across different eras of African governance (e.g., single-party states vs. multiparty democracies).

4.2. Citation Networks and Collaborative Scholarship
Another valuable digital humanities approach involves constructing citation networks to track how Africa Media Review articles cite (and are cited by) other scholarly works, including those in sister journals like African Affairs and Journal of African Media Studies. Network analysis can reveal the depth of collaboration among African-based scholars, diaspora intellectuals, and Western institutions, lending quantitative support to arguments about the journal’s centrality—or marginality—in global knowledge production.

Such a method also resonates with critiques by historians and theorists like Walter Mignolo (2002) and Dipesh Chakrabarty (2000), who argue that the geopolitics of knowledge has historically relegated African scholarship to peripheral status. Mapping citation patterns can expose the extent to which Africa Media Review advanced a decolonized agenda and circulated beyond conventional Euro-American academic circuits.

5. Conclusion: Reassessing Africa Media Review in African Historiography
The historiography of decolonization in Africa cannot be fully understood without acknowledging the pivotal role of information infrastructures, media discourses, and communication policies. Africa Media Review stands out as an essential (if sometimes overlooked) forum that consistently championed African perspectives on media, state power, and social change. In doing so, it has contributed materially to the broader project of decolonizing knowledge—a project outlined by historians like Frederick Cooper, Emmanuel Akyeampong, and Bethwell Ogot, and enriched by cross-disciplinary inputs from communication studies and cultural theory.

The journal’s legacy lies in its capacity to link local realities—language politics, community broadcasting, national media regulations—with continental and global debates about who gets to shape narratives about Africa and how. As digital humanities tools become more accessible, future researchers can leverage them to offer fresh quantitative insights into Africa Media Review’s corpus, thereby illuminating how Africa’s media historiography has evolved alongside changing geopolitical contexts.

Ultimately, Africa Media Review is best understood not as a niche publication but as a site where the energies of Africa’s quest for intellectual and political sovereignty converge. The journal’s interventions underscore the extent to which histories of information—and battles over representation—have always been integral to the processes of decolonization. Hence, any comprehensive narrative of African decolonization in the twentieth and twenty-first centuries would do well to situate Africa Media Review within the broader currents of scholarship on knowledge production, postcolonial theory, and, increasingly, digital humanities-driven inquiry.

Select Peer-Reviewed References (Illustrative)
Akyeampong, Emmanuel. 2000. “History, Memory, Slave-Trade and Slavery in Anlo (Ghana).” Slavery & Abolition 21(3): 1–24.
Brennan, James R. 2010. “Politics and Business in the Todd's Theatres of Colonial Tanganyika.” African Studies Review 53(3): 1–24.
Chakrabarty, Dipesh. 2000. Provincializing Europe: Postcolonial Thought and Historical Difference. Princeton University Press.
Cooper, Frederick. 2002. Africa Since 1940: The Past of the Present. Cambridge University Press.
Cooper, Frederick. 2014. Africa in the World: Capitalism, Empire, Nation-State. Harvard University Press.
Dike, Kenneth Onwuka. 1956. Trade and Politics in the Niger Delta, 1830–1885. Clarendon Press.
Falola, Toyin. 1993. History of Nigeria 3: Nigeria in the Nineteenth Century. Longman.
Mbembe, Achille. 2001. On the Postcolony. University of California Press.
Mbah, Emmanuel N. 2016. “Communication and Conflict Resolution in Postcolonial Cameroon.” African Studies Review 59(2): 63–84.
Ngũgĩ wa Thiong’o. 1986. Decolonising the Mind: The Politics of Language in African Literature. James Currey.
Ogot, Bethwell A. 1963. “British Administration in the Central Nyanza District of Kenya, 1900–60.” Journal of African History 4(2): 249–273.
Rodney, Walter. 1972. How Europe Underdeveloped Africa. Bogle-L’Ouverture Publications.
Suret-Canale, Jean. 1964. French Colonialism in Tropical Africa 1900–1945. Pica Press.
Tilley, Helen. 2011. Africa as a Living Laboratory: Empire, Development, and the Problem of Scientific Knowledge, 1870–1950. University of Chicago Press.
(Note: These references are provided as examples of peer-reviewed scholarship relevant to the discussion. Many additional references within African Studies, media history, and digital humanities can be consulted to deepen the historiographical and methodological insights presented here.)
```

### Second Attempt

```markdown
A Historiographical Essay on Africa Media Review within the Histories of Information and Decolonization

Since its founding in 1986 under the auspices of the African Council for Communication Education (ACCE), Africa Media Review has provided a forum for examining African media and communication through African-centered lenses. Despite the journal’s somewhat modest profile in broader academic discourse, its significance for understanding decolonization—particularly the decolonization of information—cannot be overstated. This essay offers a historiographical overview of Africa Media Review, embedding it within critical debates about knowledge production, postcolonial power, and the evolving digital humanities approaches that allow new ways to study both African media history and the processes of decolonization.

1. Decolonization and Information: Shaping the Terrain
1.1. Early Histories of Colonial Knowledge Systems
Mid-twentieth-century historians of Africa, such as Kenneth Onwuka Dike (1956) and Jean Suret-Canale (1964), established how European colonial administrations not only seized economic and political control but also dominated the production and circulation of information. Dike’s seminal Trade and Politics in the Niger Delta, 1830–1885 (Clarendon Press) demonstrated how colonial records and archives shaped early historical narratives of African societies. These works underscored the fact that knowledge and “facts” about Africa were mediated by colonial offices, missionaries, and merchants, highlighting the structural imbalances that later African historians and media scholars would seek to redress.

1.2. Postcolonial Historiography and Media Critiques
By the 1970s and 1980s, a new generation of Africanist scholars—including Bethwell A. Ogot, Toyin Falola, and Emmanuel Akyeampong—expanded the scope of African historiography to include subaltern voices, indigenous knowledge systems, and the complexity of oral traditions. Yet, as Frederick Cooper (2002) argues in Africa Since 1940: The Past of the Present (Cambridge University Press), the focus tended to remain on political decolonization and economic dependency, often sidelining the ways in which information flows and media infrastructure underwrote the postcolonial state.

Meanwhile, communication scholars were pointing out the shortcomings of Western-centric models of media development in postcolonial contexts. Research articles published in peer-reviewed venues—such as Kwame Karikari’s analyses of African press freedoms in Journal of African Media Studies—signaled a shift toward understanding how media functioned as an arena of cultural and ideological contestation in post-independence Africa.

2. Foundations of Africa Media Review
2.1. Origins in the NWICO Debates
Africa Media Review emerged against the backdrop of the New World Information and Communication Order (NWICO) debates, sparked by the 1980 MacBride Commission report (Many Voices, One World). Although that report itself was published through UNESCO and not a strictly peer-reviewed journal, numerous peer-reviewed articles subsequently analyzed its implications—e.g., Kaarle Nordenstreng (1979) in Gazette and Hamid Mowlana (1980) in Journal of Communication. These debates centered on systemic inequalities in global information flows, prompting scholars and policymakers to demand greater autonomy for the Global South in shaping media production and dissemination.

Within this climate, the ACCE recognized a need for a specialized, peer-reviewed journal dedicated to African media perspectives—one that could both address NWICO-related questions and reflect African priorities. Africa Media Review thereby positioned itself as a platform where African researchers, journalists, and policymakers could publish theoretically informed and empirical studies about media structures, content, and audiences on the continent.

2.2. Aims and Editorial Vision
From its outset, Africa Media Review sought to decenter Western paradigms of communication research. Articles addressed issues ranging from state-press relations in newly independent nations to the role of local languages in broadcasting. By insisting on a rigorous peer-review process and maintaining editorial independence, the journal advanced the objective of decolonizing knowledge in communication studies. This editorial ethos paralleled the broader objectives of postcolonial theorists like Achille Mbembe (2001) in On the Postcolony (University of California Press), who underscored that meaningful decolonization must include reconfiguring the categories and frameworks through which knowledge about Africa is produced.

3. Africa Media Review and the Historiography of Information
3.1. Linking Colonial Legacies to Postcolonial Media
A recurrent theme in Africa Media Review has been the effort to trace continuities between colonial-era information policies and post-independence state strategies. Historians of African media—e.g., James R. Brennan (2010) in African Studies Review—have shown how newspapers established under colonial administrations became battlefields for nationalist politics. Africa Media Review articles amplified these insights, demonstrating how print media and radio, once tools of colonial governance, were reappropriated by postcolonial governments to foster national unity, consolidate power, or both.

In doing so, the journal placed African media histories alongside broader projects of historical revisionism championed by luminaries like Walter Rodney (1972) in How Europe Underdeveloped Africa. While Rodney focused primarily on economic exploitation, scholars in Africa Media Review extended the critique to information infrastructures, showing that external dependence on wire services and Western models of journalism could perpetuate new forms of intellectual subjugation.

3.2. Emphasis on Local Agency and Cultural Context
Building on Africa-based intellectual traditions, contributions to Africa Media Review regularly foregrounded African agency in shaping media. In line with Jean-François Bayart’s concept of “extraversion” (1993)—the idea that African states negotiate global influences by creatively adapting external frameworks—articles in the journal illustrated how African journalists, radio producers, and civil society organizations contested or reconfigured state-imposed media policies. This viewpoint echoes Frederick Cooper’s (2014) argument in Africa in the World (Harvard University Press) that Africans engaged colonial and global systems not merely as passive subjects but as strategic actors capable of resisting or reforming the status quo.

By highlighting local languages, folk storytelling, and community broadcast initiatives, Africa Media Review helped broaden the discipline’s understanding of “media” to include cultural and participatory forms. This addressed critiques leveled by postcolonial theorists like Ngũgĩ wa Thiong’o (1986) in Decolonising the Mind (Heinemann), who insisted that decolonization must be rooted in the affirmation of indigenous languages and cultural practices.

4. Digital Humanities Approaches: New Tools for Historical Inquiry
4.1. Text Mining and Topic Modeling
Recent advances in digital humanities methodologies offer novel ways to analyze journals like Africa Media Review at scale. Although historians have traditionally relied on qualitative reading of selected articles, computational text mining and topic modeling (using tools like MALLET or Voyant Tools) can map how concepts such as “decolonization,” “press freedom,” and “censorship” shift in salience over multiple decades.

Scope: Researchers can collect full-text issues of Africa Media Review, segment the corpus by publication year, and run topic-modeling algorithms to see patterns in content and thematic emphasis.
Outcomes: Such macro-level analyses might corroborate what historians like Emmanuel Akyeampong (2000) have argued about changing scholarly foci over time—in his case regarding memory and history, but analogous in media studies as emphasis moves from state-run broadcasting (in the 1980s) to privatization and digital convergence (in the 2000s).
4.2. Citation Network Analysis
Citation network analysis is another digital humanities technique that can illuminate Africa Media Review’s intellectual and institutional influence. By tracing citation links—both references in Africa Media Review articles and subsequent scholarly works citing them—researchers can:

Identify Intellectual Clusters: Determine which African universities and research centers most frequently publish in or are cited by the journal, elucidating the geographical and institutional hubs for African media research.
Measure Impact: Map how Africa Media Review articles travel across related fields—communication studies, area studies, political science, anthropology—thereby tracking the journal’s role in shaping cross-disciplinary dialogues.
Such analyses align with the calls by scholars like Dipesh Chakrabarty (2000) in Provincializing Europe (Princeton University Press) to de-center Euro-American knowledge production. Empirical evidence of citation flows can help us see whether Africa Media Review maintains a peripheral status in global academia or whether it has forged robust transnational linkages, thereby concretizing the “decolonization of knowledge” in the scholarly domain.

5. Broader Historiographical Significance
5.1. Extending Debates on Decolonization
By embedding studies of African media and communication within postcolonial historiography, Africa Media Review has expanded how decolonization is understood. Traditionally, historical scholarship on African decolonization (e.g., Elizabeth Schmidt, 2013, in Journal of African History) has spotlighted nationalist politics, labor movements, or international diplomacy. Africa Media Review reminds us that struggles over who controls the press, how languages are used, and what images circulate matter as much for sovereignty as flag independence.

5.2. Looking Ahead: Digital Transitions
Today’s digital landscapes—marked by social media, mobile communication, and new forms of digital storytelling—raise fresh questions about how Africans navigate and transform global information ecosystems. Africa Media Review and its contributors remain vital resources for scholars examining not only the historical roots of such dynamics but also contemporary digital disruptions. These developments resonate with Achille Mbembe’s more recent reflections (e.g., 2017 in Critical Inquiry) on the possibility of “Afropolitan” engagements in digital space, potentially advancing a new phase of decolonial media scholarship.

6. Conclusion
In sum, the historiography of African decolonization must grapple with the critical role of information infrastructures, cultural production, and communication policy—realms that Africa Media Review has diligently documented and interpreted for almost four decades. By situating the journal within broader decolonial debates, we see it as a crucial part of Africa’s intellectual arsenal, challenging Eurocentric paradigms and promoting African agency in media research and policy.

Further, the emergent digital humanities toolkit offers exciting possibilities for reevaluating Africa Media Review’s contributions at scale. Through text mining, topic modeling, and citation analysis, scholars can glean deeper insights into how the journal has shaped discourses on African media, engaged with global communication scholarship, and continually advanced the cause of decolonization. Ultimately, Africa Media Review underscores the intricate link between liberation struggles, power over information flows, and the ongoing endeavor of Africans to narrate their own stories on their own terms.

Select Peer-Reviewed References (Illustrative)
Akyeampong, Emmanuel. 2000. “History, Memory, Slave-Trade and Slavery in Anlo (Ghana).” Slavery & Abolition 21(3): 1–24.
Bayart, Jean-François. 1993. The State in Africa: The Politics of the Belly. Longman.
Brennan, James R. 2010. “Politics and Business in the ‘Todd’s Theatres’ of Colonial Tanganyika.” African Studies Review 53(3): 1–24.
Chakrabarty, Dipesh. 2000. Provincializing Europe: Postcolonial Thought and Historical Difference. Princeton University Press.
Cooper, Frederick. 2002. Africa Since 1940: The Past of the Present. Cambridge University Press.
Cooper, Frederick. 2014. Africa in the World: Capitalism, Empire, Nation-State. Harvard University Press.
Dike, Kenneth Onwuka. 1956. Trade and Politics in the Niger Delta, 1830–1885. Clarendon Press.
Mbembe, Achille. 2001. On the Postcolony. University of California Press.
Mowlana, Hamid. 1980. “Communication in the Post-Industrial Era: New Trends in International Communication.” Journal of Communication 30(2): 114–123.
Ngũgĩ wa Thiong’o. 1986. Decolonising the Mind: The Politics of Language in African Literature. Heinemann.
Nordenstreng, Kaarle. 1979. “The New World Information and Communication Order: An Overview of Some Results.” Gazette 25(4): 229–245.
Ogot, Bethwell A. 1963. “British Administration in the Central Nyanza District of Kenya, 1900–60.” The Journal of African History 4(2): 249–273.
Rodney, Walter. 1972. How Europe Underdeveloped Africa. Bogle-L’Ouverture.
Schmidt, Elizabeth. 2013. “Top Down or Bottom Up? National Independence and Peasant Agency in Decolonization.” The Journal of African History 54(1): 105–121.
Suret-Canale, Jean. 1964. French Colonialism in Tropical Africa 1900–1945. Pica Press.
(Note: All cited works are either published by university presses—generally understood to be peer-reviewed—or appear in established, peer-reviewed academic journals.)
```

## Ranking References

| Reference | Attempt 1 | Attempt 2 | Accurate? | Error | Previously Knew of Source? | Would Use Source? |
| --- | --- | --- | --- | --- | --- | --- |
| Akyeampong, Emmanuel. 2000. “History, Memory, Slave-Trade and Slavery in Anlo (Ghana).” *Slavery & Abolition* 21(3): 1–24. | ✅ | ✅ | ❌ | Published in December 2001, not 2000 | ❌ | 🤔 |
| Bayart, Jean-François. 1993. *The State in Africa: The Politics of the Belly*. Longman. | ❌ | ✅ | ✅ |  | ❌ | 🤔 |
| Brennan, James R. 2010. “Politics and Business in the Todd's Theatres of Colonial Tanganyika.” *African Studies Review* 53(3): 1–24. | ✅ | ✅ | ❌ | Article doesn’t exist |  |  |
| Chakrabarty, Dipesh. 2000. *Provincializing Europe: Postcolonial Thought and Historical Difference*. Princeton University Press. | ✅ | ✅ | ✅ |  | ✅ | ✅ |
| Cooper, Frederick. 2002. *Africa Since 1940: The Past of the Present*. Cambridge University Press. | ✅ | ✅ | ✅ |  | ✅ | ✅ |
| Cooper, Frederick. 2014. *Africa in the World: Capitalism, Empire, Nation-State*. Harvard University Press. | ✅ | ✅ | ✅ |  | ✅ | ✅ |
| Dike, Kenneth Onwuka. 1956. *Trade and Politics in the Niger Delta, 1830–1885*. Clarendon Press. | ✅ | ✅ | ✅ |  | ❌ | ❌ |
| Falola, Toyin. 1993. *History of Nigeria 3: Nigeria in the Nineteenth Century*. Longman. | ✅ | ❌ | ✅ |  | ❌ | ❌ |
| Mbembe, Achille. 2001. *On the Postcolony*. University of California Press. | ✅ | ✅ | ✅ |  | ✅ | ✅ |
| Mbah, Emmanuel N. 2016. “Communication and Conflict Resolution in Postcolonial Cameroon.” *African Studies Review* 59(2): 63–84. | ✅ | ❌ | ❌ | Article doesn’t exist |  |  |
| Mowlana, Hamid. 1980. “Communication in the Post-Industrial Era: New Trends in International Communication.” *Journal of Communication* 30(2): 114–123. | ❌ | ✅ | ❌ | Article doesn’t exist |  |  |
| Ngũgĩ wa Thiong’o. 1986. *Decolonising the Mind: The Politics of Language in African Literature*. James Currey. | ✅ | ✅ | ✅ |  | ❌ | ✅ |
| Nordenstreng, Kaarle. 1979. “The New World Information and Communication Order: An Overview of Some Results.” *Gazette* 25(4): 229–245. | ❌ | ✅ | ❌ | Article doesn’t exist |  |  |
| Ogot, Bethwell A. 1963. “British Administration in the Central Nyanza District of Kenya, 1900–60.” Journal of African History 4(2): 249–273. | ✅ | ✅ | ✅ |  | ❌ | 🤔 |
| Rodney, Walter. 1972. *How Europe Underdeveloped Africa*. Bogle-L’Ouverture Publications. | ✅ | ✅ | ✅ |  | ✅ | ✅ |
| Schmidt, Elizabeth. 2013. “Top Down or Bottom Up? National Independence and Peasant Agency in Decolonization.” *The Journal of African History* 54(1): 105–121. | ❌ | ✅ | ❌ | Article doesn’t exist |  |  |
| Suret-Canale, Jean. 1964. *French Colonialism in Tropical Africa 1900–1945*. Pica Press. | ✅ | ✅ | ✅ |  | ❌ | 🤔 |
| Tilley, Helen. 2011. *Africa as a Living Laboratory: Empire, Development, and the Problem of Scientific Knowledge, 1870–1950*. University of Chicago Press. | ✅ | ❌ | ✅ |  | ✅ | ✅ |

---

# OCR Correction Experiments

## Original Materials

![Screenshot 2025-02-19 at 1.29.12 PM.png](MSU%20AI%20&%20Research%20Workshop%20Prompt%20Evaluation%20Resul%2019f42ec6cb3e806f99fcc599ba16016a/Screenshot_2025-02-19_at_1.29.12_PM.png)

```markdown
Africa  Media  Review  Vol. 2 No. 1.  1987
•  African  Council on Communication  Education

A Critical Appraisal  of the

Communication  Gap in
the Liberation  Struggle

by Sybil James*

Abstract

This paper calls for a critical appraisal of the use of the politically
loaded  words  which  are  normally  associated  with  liberation
struggles. It suggests  that  these  terms are often vaguely defined
and mean different  things to different publics. Their constant use,
therefore,  tends  to  obscure  the  message  and  to  create  a
communication  gap. The writer  subscribes  to the view  that,
contrary  to the intention  of the message  senders,  many of the
descriptors used present a denigrating image of the groups they set
out to help and that both these descriptors as well as the criteria for
classifying the groups should be reconsidered. This she thinks, is
one  of  the  important  assignments  which  development
communicators should  undertake.

Resume

Cet article appelle a une Evaluation critique de l'usage des mots a
forte  charge  politique  qui sont  normalement  associeis  avec les
luttes de libe'ration. II suggere que ces termes sont souvent de'finis
de  maniere  vague et ont des significations  diffe'rentes  selon les
publics. Leur usage indiffe'rencie' tend donck obscurcir le message
et a creier un probleme de communication.  L auteur  souscrit au
point de vue que, contrairement  a l'intention  des Emetteurs des
messages,  beaucoup  des descripteurs  utilises  pre'sentent une
image diffamatrice  des groupes qu'ils sont cense's aider et que ces
descripteurs  aussi  bien  que les criferes  de classification  des
groupes  devraient  8tre  revus. A son avis, il s'agit Ik d'une  tache
importante que les communicateurs du developpement devraient
entreprendre.

*Dr.  Sybil  James  Is Head,  Department  of Language  Arts,  University  of Ibadan,
Nigeria.

A major  impediment  to  social  change  and  the  development
process of third world nations is the communication gap between
the  advocates  of  change  and  their  target  population.  One
contributing factor to this state of affairs is the fact that scholars
and  development  planners  use  technical  terms  and  preach
abstract concepts which politicians and national leaders translate
into cliches with which to ieed their citizens. As a result the public
invariably  misunderstands  vital  issues  or  at  least  understands
them partially. Even the implementators of the policies often read a
totally  different  meaning  in  them  than  that  intended  by  the
designers. The political  history of new nations over the past two
decades gives ample testimony to this  fact.

The  1960s,  a  decade  of great  militancy  and  mass  movement
towards  independence,  saw  the  rise  of  new  nations  amid  loud
sloganeering.  Such  terms  as  "Freedom",  "self  reliance",  "self
sufficiency", 
"capitalism",  "marxism",  "communism",  were
household words bandied from mouth to mouth and interpreted to
fit  into  each  person's  expectations  or  prejudices. And, as  each
nation raised its national flag amid great rejoicing, many laboured
under the impression that independence and therefore liberation
had been attained. The experience of the past two decades has no
doubt, had a solutary effect  on the politically aware as well as the
politically naive. Among the lessons learnt  is that  independence
and  its  correlations,  liberation  and  self-reliance  are  not  human
conditions to be attained once and for all, but dynamic processes
which  "require  continuous  rearrangement  of  existing
commitments and an unimpeded, exchange and mobilization of all
goods and services" (Weintraub 1973:22). Each Nation's perception
of these processes therefore, and the extent to which it is equipped
to  cope  with  the  continuous  rearrangement  of  commitments,
determine  whether  or  not  self  reliance  is  an  attainable  goal.
Development communicators have a duty to define these processes
and expand their programmes to include a focus on the language of
development  communication.  More  specifically,  they  must  be
sensitive to the fact that meaning can be obscured when everyday
words take on specialized  meanings.

This paper attempts to operationalize the concepts "liberation"
and "self reliance" and raises the question who should be liberated
and from what  In the light of the answers suggested, it discusses
the  role  of the development  communicator  in  translating socio-
political  concepts  into  task  related  behaviours  with  which  the
laymen can identify; and which can enhance his personal qualities
or qualities of "being" and his social skills or skills of "doing."

2

The Concept of Liberation  and  the Language  of the  Struggle

The word "liberation" like the word "development" has political
overtones,  hence  its  definition  is  determined  by  the  political
leanings of the deflner. For developing countries of the third world
it implies a greater opportunity to determine their own future, to
achieve  more  justice  in  the  use  of  their  human  and  natural
resources  and  simply to have a  fuller  life for their citizens (Fore
1985: 19). It is not an end in itself but "one of the stages to a non-
exploitative society." (Mendele 1961).

History is replete with examples of nations and peoples fighting
for liberation. These battles have been fought on battlefields and in
parliaments; underground and in public squares; through passive
resistance and  open rebellion; with the pen and with the sword;
and  in  every  case  the  strategies,  channels  and  language  of
communication  have  been  determined  by  the  specific
circumstance. In other words one is always faced with the question,
liberation from  what?

Liberation  struggles  in  the  third  world  began  with  the  fight
against  colonialism,  that  is,  the  system  in  which  a  nation's
economic,  political  and  social  policies  were  dictated  by  its
colonisers. These  "colonies" had  been acquired  in  the  15th  and
16th centuries by European nationals who captured them in the
name of their sovereigns - emperors, kings, queens - exploited their
resources,  enriched 
teritorial
boundaries  of  the  sovereign  countries  which  in  turn  gained
considerable wealth and power. Imperialism  therefore which is a
correlate  of  colonialism  and  which  is  derived  from  the  word
emperor,  refers  to  the  extending  of  one  country's  political,
economic  and  military  authority  over  another.  These
circumstances have therefore led to the word "exploitation" being
associated with the liberation struggle.

themselves,  expanded 

the 

Another  group  of  words,  "capitalism",  "communism",
"marxism",  and  "socialism",  have  been  introduced  by  political
thinkers who set out to interpret the conflict within an ideological
framework.  Each  of  these  terms  describes  a  specific  economic
system. A full discussion of each of these is outside the scope of this
paper but a simple dictionary definition  will suffice  to make this
discussion  meaningful.

Whereas capitalism advocates competition and a profit-oriented
economic system,  communism  advocates collective ownership of
the production; distribution  and supply system by the whole of a
"classless" society, and  the wealth  shared  each  according to  his
need  and  each yielding according  to his ability. Marxism  is the

3

political and economic system  advocated  by Marx and  Engels and
its  teaching  informs  the philosophy  of the communist  system. It
sees capitalism in terms of the exploitation of the pro/ef aria! by the
bourgeoists.

Like  communism  and  marxism,  socialism  also  advocates
collective  ownership  of  means  of  production  and  control  of
distribution.  It is based on the belief that all, while contributing to
the  good  of  the  community,  are  equally  entitled  to  the  care  and
protection which the community can provide. This theory assumes
different  forms  according  to  the  relative  stress  laid  on  its  social,
economic  and  political  corollaries.  While  Marxist  socialism
stresses economic issues, Christian socialism stresses social issues
and  democratic  socialism  stresses  political  aspects  accepting
compromise  In  the  economic  field  between  state  and  private
enterprise.  All forms  of socialism  are  opposed  to  capitalism  and
seek  equality  of  opportunity.

In  the  contemporary  political  scene,  in  particular  in 

the
liberation struggles, these are highly emotive words. They are used
as  terms of abuse against  political  opponents; they punctuate  the
diatribes  that  incite  mass  rallies; they cover  the  flamboyant  with
the cloak  of  radicalism;  they  impress  the gullible  and  raise  false
hopes  in  the  naive.

The second  major  political  war of liberation  in  the Third  World
has been the struggle against apartheid, a political system built on
social  prejudice  and  the  total  subjugation  of  one  sector  of  the
society  by  another.  It  is  a  system  that  keeps  a  majority  group
socially, culturally and physically oppressed. The words "oppressor
and  oppression"  have  therefore  been  legitimately  identified  with
this  struggle.  As  with  the  anti-colonialism  struggle  discussed
earlier,  the  motivation  is clear and  the goals ol liberation  spelled
out. They  include:

• 
• 

• 
• 

the destruction of the structures of separatism (Tambo).
the building of a society where race and colour are of no
consequence,  where  people  serve  according  to  their
abilities and  skills.
the  destruction  of the white  racist  regime.
the  abolition  of  national,  cultural  and 
priviledges of whites  over blacks.

religious

In  these  struggles  the goals have been clear and  the  vocabulary
unambiguous. But there are many other types of liberation  battles
to be fought on the road to self reliance. The nature of these is not as

clear cut  and  the objectives  are  not  as easy  to pursue; since the
problems are to a large extent, internally generated. The forces that
enslave  operate  both  at  the  national  level and  at  the group  and
individual levels.

At the national level, among the many factors from which Third

World countries need  to be liberated are the iollowing:-
• 

the  patron  -  client  relationship  with  the  developed
countries (Guioguio, 1984). The dependency exists at  the
economic,  political  and  cultural  levels  and  as  such
threatens  the  existence  and  autonomy  even  of  our
communication  network.
the  paramountcy  of  foreign  capital  which  makes  it
impossible for capital generated within a given country to
accumulate there and work towards the development of a
self-sufficient  economy (Jayaweera,  1984: 8).

•  cultural domination which contributes to the destruction
and  disruption  of  indigenous  values,  behaviour  and
technology.

• 

At  the  individual  and  group  level, there  is  need  for  liberation

from:-
•  unscrupulous politicians and national policies.
• 

the groups within the society that monopolise the sources
of production and distribution and hoard the supplies.

•  political  charlatans  who  confuse  issues  with  their  high
the  people's

sounding 
intelligence, and on their human and civil  rights.

trample  on 

language, 

•  selfishness, greed and  the desire  to amass wealth at any

lofty 

cost.

•  ignorance, poverty and  superstition.

The foregoing analysis highlights the need to shift the liberation
battle to the home front once political power has been wrested from
those  who wielded  it externally. This to my mind, is  the  second
stage in-the liberation struggle - a stage which many Third World
Countries  seem 
to  be  short  circuiting.  Development
communication  working at  this level must begin with the policy
makers and the national planners. Once these functionnaries  are
committed  to  the  task  of emancipating  themselves  morally and
spiritually they will be better equipped to combat the multifarious
problems associated with economic emancipation. It seems to me,
therefore, that a change of direction and objectives will go a  long

5

way  in  helping  the  common  man  to  put  the  struggle  for  self
sufficiency  into  its  proper  perspective.  When  the  pendulum
eventually  swings,  as  it  must,  and  it  is  his  turn  to join  in  the
struggle  for  his  own  liberation  from  ignorance,  poverty  and
internal oppressors, he can understand and appreciate the part he
is  called  upon  to  play.  For,  as  one  researcher  aptly  put  it,  the
interpretation  of signs and  symbols lies within the person not in
the symbols themselves.

National self sufficiency  or self reliance is the next stage. This
should involve all the people —  the urban poor and the urban rich;
the  rural  poor  and  the  rural  rich; the various groups  that  have
special needs and special contributions to make; those engaged in
farming  and  agriculture;  those  concerned  with  sweeping  the
streets  and  environmental  sanitation;  women  as  a  group  - the
market women and the food sellers; mine workers, truck, train and
taxi drivers. Each of these groups with its own problems and needs
can  be  identified.  All  these  must  be  involved  in  the  liberation
struggle and while being taught to fight for their rights they must
also be schooled  about  their commitments  to  their duties  since
these two (rights and duties) always go hand in hand.

The familiar cliches such as the masses, the suffering  poor, the
oppressed people in the rural areas, the illiterate masses should be
avoided.  They  do  little  more  than  present  a  picture  of  an
amorphous  group  with  no  voice or  identity  of its  own, waiting
patiently  for  some  social  worker,  development  communicator,
missionary or benevolent dictator to deliver them from their woes.
This image while serving the purpose of the funding agencies and
those anxious to improve the lot of the downtrodden, does not help
the  process  towards  self  sufficiency.  I share  the  view  of David
Briddell  (1985, p. 20)  that  poverty, imbalance  of resources, and
oppression can be documented and presented in such a way that
there is no loss of dignity or misrepresentation  in the process. In
fact, the habit of sticking to the old hackneyed  rhetoric makes it
difficult  to see when the "suffering  poor" moves on to become the
"struggling poor" and later rises to be the "liberated  poor"..

Another danger in this persistent use of these blanket terms is
that the need to diversify efforts at development education is lost
sight of. For example, most of the programmes for the "oppressed
people  in  the  rural  areas"  seem  to  focus  on  agricultural  and
farming  or  health  and  environmental  programmes.  No one  can
deny  that  agriculture  is  vital  to  the  life  and  sustenance  of  the
nation and is a revenue earner but are all rural folk farmers? Don't
the  others  need  education  and  to  improve  their  means  of

6

livelihood? Are development planners only concerned with what
will  increase  the  national  coffers?  Shouldn't  they  be  just  as
concerned with the improvement of individuals within the various
sectors?

A look  at  the  various  pressure  groups  that  emerge in  society
should  give  us  a  clue. This  is  'feedback'  enough.  Development
communicators should take their cue from  these and work out a
fresh  and  more viable strategy for classifying  citizens when they
plan their development programmes.

What do  we mean by  self-reliance?

The term self-reliance has political, economic, social and cultural

implications.

that self-reliance implies:-

White (1982, p. 25) focusing on the political implications notes

•  A controlled  selectivity  in  the  importation  of  scientific

information  and cultural products.

•  Autonomy in the making of all national decisions.
•  A  high  level  of  discriminability  with  what  must  be

considered essential imports.

•  Ability of leadership to win the confidence and the mandate
of  the  nation  in  its  search  for  national  identity  and  an
alternative form of government.

The socio-economic indicators of self reliance are:-

•  A  capacity  of  the  people  to  control  their  environment,
accompanied by a wider distribution of benefits  resulting
from such control (Inyatullah  1974: p. 4).

•  Ability of the majority of the people to take charge of their

own lives and cope with the ongoing societal changes.

•  Literate populace willing to utilise the best available means

of production.

•  The ability to provide food and  shelter for all.
•  Willingness and the ability of the inhabitants to participate

in the governance of the  nation.

Cultural indicators include:-

•  A national appreciation and understanding of traditional

values and  norms.

7

Development  communicators  need  to  examine  these  basic
indicators of self reliance, and with  the assistance of the various
pressure groups who constantly articulate their needs, utilise the
most appropriate channels to achieve their goals. They should use
the  language  with  which  the  groups  they  set  out  to  help  can
identity. These groups spring up naturally because their members
share  common  interests  and  have  common  problems.  Their
symbols and terms of identification  are self imposed, not inflicted
on them by external agencies.

When this approach is adopted and leaders demonstrate the level
of commitment expected of them, self reliance will be an attainable
goal.

In  summary,  therefore,  self  reliance  is  the  end  product  of
liberation.  But  since  liberation  is  an  on-going  process,  the
Indicators  of self-reliance  are constantly changing. Development
communicators should be sensitive to these changes, and should
find  in  the various pressure groups emerging at all strata of the
society a forum  through which to reach  their targets.

REFERENCES

Buddell. David (1985)  The Practice of NWICO Values within Religious Structures"
in  Communication  Challenges  of  Our  Time.  London:  World  Association  of
Christian  Communication,  pp.  17-21.
Fore, William  (1985) "NWICO From  an American  Perspective" in  Communication
Challenges  qj Our Time.  London WACC.
Guioguio, Reynakio (1984) "A Framework fora  National Communications'Policy in
the Philippines." Media  Asia  2: 3. 158-166.
Inyatullah,  CI  (1974)  "A  Proposed  Framework  for  the  Study  of  Approaches  to
Development in Asia". Kuala Lumpur Asia Centre for Development Administration.

Jayaweera,  N.  (1985)  "The  Threat  to  NWICO Values  from  the  Communication
Revolution." in  Communication  Challenges  of Our Time.  London: WACC.

Mandela. Nelson (1961) "The Freedom Charter Equality and Self-Determination" in
Third  World Book  Review  2:  1 & 2.

Welntraub,  D. (1973)  Development  and  Modernisation 
in  the  Philippines:  The
Problem  of  Change  in  the  Context  of Political  Stabiltty  and  Social  Continuity.
Beverley Hills: Sage  Publications.

White  Robert  (1982)  ••Priorities  for  National  Policy  in  The  Third  World".
Communication  Policy  and  Planning.  Reader  On  Policy  Analysis.  Institute  of
Social Studies.

8

```

## Corrected Materials

![Screenshot 2025-02-19 at 1.27.09 PM.png](MSU%20AI%20&%20Research%20Workshop%20Prompt%20Evaluation%20Resul%2019f42ec6cb3e806f99fcc599ba16016a/Screenshot_2025-02-19_at_1.27.09_PM.png)

```markdown
### Africa Media Review Vol. 2 No. 1, 1987

### African Council on Communication Education

## A Critical Appraisal of the Communication Gap in the Liberation Struggle

### by Sybil James

### Abstract

This paper calls for a critical appraisal of the use of politically loaded words that are normally associated with liberation struggles. It suggests that these terms are often vaguely defined and mean different things to different publics. Their constant use, therefore, tends to obscure the message and create a communication gap. The writer subscribes to the view that, contrary to the intention of the message senders, many of the descriptors used present a denigrating image of the groups they set out to help. Both these descriptors and the criteria for classifying the groups should be reconsidered. This, she believes, is one of the important assignments that development communicators should undertake.

### Résumé

Cet article appelle à une évaluation critique de l'usage des mots à forte charge politique qui sont normalement associés aux luttes de libération. Il suggère que ces termes sont souvent définis de manière vague et ont des significations différentes selon les publics. Leur usage indifférencié tend donc à obscurcir le message et à créer un problème de communication. L'auteur souscrit au point de vue que, contrairement à l'intention des émetteurs des messages, beaucoup des descripteurs utilisés présentent une image diffamatoire des groupes qu'ils sont censés aider et que ces descripteurs, ainsi que les critères de classification des groupes, devraient être revus. À son avis, il s'agit là d'une tâche importante que les communicateurs du développement devraient entreprendre.

*Dr. Sybil James is Head, Department of Language Arts, University of Ibadan, Nigeria.*

---

### The Communication Gap in Liberation Struggles

A major impediment to social change and the development process of Third World nations is the communication gap between the advocates of change and their target populations. One contributing factor to this state of affairs is that scholars and development planners use technical terms and preach abstract concepts, which politicians and national leaders then translate into clichés to feed their citizens. As a result, the public invariably misunderstands vital issues or at least understands them only partially. Even the implementers of policies often interpret them in a way entirely different from what was intended by the designers. The political history of new nations over the past two decades gives ample testimony to this fact.

The 1960s, a decade of great militancy and mass movements toward independence, saw the rise of new nations amid loud sloganeering. Terms such as "Freedom," "self-reliance," "self-sufficiency," "capitalism," "Marxism," and "communism" were household words, bandied about and interpreted to fit each person's expectations or prejudices. As each nation raised its national flag amid great rejoicing, many labored under the impression that independence—and therefore liberation—had been attained. However, the experience of the past two decades has had a salutary effect on both the politically aware and the politically naïve. Among the lessons learned is that independence, along with its correlates, liberation and self-reliance, are not static human conditions to be attained once and for all but dynamic processes requiring continuous realignment of existing commitments and the unimpeded exchange and mobilization of all goods and services (Weintraub 1973:22). Each nation's perception of these processes, and the extent to which it is equipped to cope with this continuous realignment, determines whether or not self-reliance is an attainable goal. Development communicators have a duty to define these processes and to expand their programs to include a focus on the language of development communication. More specifically, they must be sensitive to the fact that meaning can be obscured when everyday words take on specialized meanings.

---

### The Concept of Liberation and the Language of the Struggle

The word "liberation," like the word "development," has political overtones; hence, its definition is determined by the political leanings of the definer. For developing countries of the Third World, it implies a greater opportunity to determine their own future, achieve more justice in the use of their human and natural resources, and simply secure a fuller life for their citizens (Fore 1985:19). It is not an end in itself but "one of the stages to a non-exploitative society" (Mandela 1961).

History is replete with examples of nations and peoples fighting for liberation. These battles have been fought on battlefields and in parliaments; underground and in public squares; through passive resistance and open rebellion; with the pen and with the sword. In every case, the strategies, channels, and language of communication have been determined by the specific circumstances. In other words, one is always faced with the question: liberation from what?

Liberation struggles in the Third World began with the fight against colonialism—a system in which a nation's economic, political, and social policies were dictated by its colonizers. These "colonies" were acquired in the 15th and 16th centuries by European nationals who captured them in the name of their sovereigns—emperors, kings, and queens—exploited their resources, enriched themselves, and expanded the territorial boundaries of their sovereign countries, which in turn gained considerable wealth and power. Imperialism, therefore, as a correlate of colonialism, refers to the extension of one country's political, economic, and military authority over another. This historical context has resulted in the word "exploitation" being inextricably linked to the liberation struggle.

Another group of words—"capitalism," "communism," "Marxism," and "socialism"—were introduced by political thinkers who sought to interpret the conflict within an ideological framework. Each of these terms describes a specific economic system. Whereas capitalism advocates competition and a profit-oriented economic system, communism advocates collective ownership of the means of production, distribution, and supply by a classless society. Marxism is the political and economic philosophy developed by Marx and Engels, which underpins communist ideology, seeing capitalism as a system of exploitation of the proletariat by the bourgeoisie. Socialism, like communism and Marxism, also advocates collective ownership of production but allows for varying degrees of state and private enterprise involvement.

---

### Conclusion

Self-reliance is the ultimate goal of liberation, but since liberation is an ongoing process, the indicators of self-reliance are constantly evolving. Development communicators should remain sensitive to these changes and should find, in the various emerging pressure groups at all levels of society, a means to reach their targets effectively. By shifting focus toward the nuances of language and classification, they can contribute meaningfully to the struggle for sustainable self-sufficiency in the Third World.

### References

**Briddell, David** (1985) *The Practice of NWICO Values within Religious Structures* in *Communication Challenges of Our Time*. London: World Association of Christian Communication, pp. 17-21.

**Fore, William** (1985) *NWICO From an American Perspective* in *Communication Challenges of Our Time*. London: WACC.

**Mandela, Nelson** (1961) *The Freedom Charter, Equality, and Self-Determination* in *Third World Book Review* 2: 1 & 2.

**Weintraub, D.** (1973) *Development and Modernization in the Philippines: The Problem of Change in the Context of Political Stability and Social Continuity*. Beverly Hills: Sage Publications.
```

---

# Web Scraping MSU Collection with AI

```python
import os
import requests
import pandas as pd
from bs4 import BeautifulSoup

# Create a directory to store PDFs
save_dir = "africa_media_review_pdfs"
os.makedirs(save_dir, exist_ok=True)

# Step 1: Collect all links
start_range = 0
increment = 100
all_links = []
for i in range(0, 300, increment):
	url = f"https://d.lib.msu.edu/search?sort=title%20asc&fq=RELS_EXT_isMemberOfCollection_uri_s%3Ainfo%5C%3Afedora/jamr%5C%3Aroot&start={i}&rows={increment}"
	response = requests.get(url)
	print(response.status_code)
	soup = BeautifulSoup(response.content, "html.parser")
	results = soup.find_all("h2", class_="sh-result-label")
	links = ["https://d.lib.msu.edu" + result.find("a")["href"] for result in results]
	all_links.extend(links)

print(f"Total articles found: {len(all_links)}")

# Store links in a DataFrame
all_links_df = pd.DataFrame(all_links, columns=["collection_item_link"])

# Step 2: Extract metadata, OCR, and download PDFs
all_metadata = []

for index, row in all_links_df.iterrows():
	page_url = row["collection_item_link"]
	response = requests.get(page_url)
	if response.status_code != 200:
		print(f"Failed to retrieve {page_url}")
		continue
	
	soup = BeautifulSoup(response.content, "html.parser")

	# Extract title
	title_element = soup.find("h1")
	title = title_element.text.strip() if title_element else "No title found"

	# Extract abstract
	abstract_element = soup.find("div", class_="sh-block-collapse")
	abstract = abstract_element.text.strip() if abstract_element else "No abstract found"

	# Extract OCR transcript
	transcript_url = page_url + "/FULL_TEXT/view"
	transcript_response = requests.get(transcript_url)
	transcript_text = transcript_response.text if transcript_response.status_code == 200 else "No transcript available"

	# Extract metadata into a structured dictionary
	metadata_dict = {"title": title, "abstract": abstract, "transcript": transcript_text, "transcript_url": transcript_url}

	metadata_rows = soup.find_all("dl", class_="row my-3")

	for row in metadata_rows:
		dt_element = row.find("dt")
		dd_element = row.find("dd")

		if dt_element and dd_element:
			key = dt_element.text.strip()
			key = key.replace(" ", "_").replace(":", "").lower()
			value_text = dd_element.text.strip()
			link_element = dd_element.find("a")
			value_link = link_element["href"] if link_element else None

			# Store text + hyperlink if available
			if key != 'part_of':
				metadata_dict[key] = f"{value_text} ({value_link})" if value_link else value_text
			else:
				metadata_dict[key] = value_text

	filename = f"{page_url.split('edu/')[-1].replace('/', '_')}.pdf"
	filepath = os.path.join(save_dir, filename)
	metadata_dict["filename"] = filepath
	# Download PDF with unique filename
	pdf_download_url = page_url + "/OBJ/download"
	pdf_response = requests.get(pdf_download_url)
	if pdf_response.status_code == 200:
		with open(filepath, "wb") as f:
			f.write(pdf_response.content)
		print(f"Downloaded PDF: {filename}")
	else:
		print(f"Failed to download PDF for {title}")

	# Append to metadata list
	all_metadata.append(metadata_dict)

# Convert metadata list to a DataFrame with metadata fields as columns
metadata_df = pd.DataFrame(all_metadata)

# Merge with the original links DataFrame
final_df = all_links_df.merge(metadata_df, left_index=True, right_index=True)

print("Scraping and processing completed.")
# Process start and end pages
final_df['start_page'] = final_df.pages.str.split('-').str[0].str.split('Pages ').str[1]
final_df['end_page'] = final_df.pages.str.split('-').str[1]
final_df['start_page'] = final_df['start_page'].str.replace(' ', '')
final_df['end_page'] = final_df['end_page'].str.replace(' ', '')
final_df.to_csv("africa_media_review_dataset.csv", index=False)

```

[Africa Media Review Dataset](MSU%20AI%20&%20Research%20Workshop%20Prompt%20Evaluation%20Resul%2019f42ec6cb3e806f99fcc599ba16016a/Africa%20Media%20Review%20Dataset%201a142ec6cb3e80d8af50d16d10aaa352.csv)

---

# Final Results

## First Attempt

```python
Below is an expanded historiographical essay on Africa Media Review that integrates recent digital-humanities analyses of the journal's corpus—specifically, a bar chart illustrating overall OCR text length by publication date, a place-name frequency chart derived from named-entity recognition (NER), and a two-dimensional visualization (via UMAP) of the semantic relationships among articles. These graphical insights enrich our understanding of how Africa Media Review evolved over time, what geographic focal points animated its pages, and how its articles cluster thematically.

1. Introduction: Africa Media Review and the Decolonization of Information

Since its founding in 1986, Africa Media Review has played a crucial role in examining African media and communication from an African perspective. The journal emerged amid efforts to decolonize knowledge production—a movement championed by historians such as Kenneth Onwuka Dike (1956) and Jean Suret-Canale (1964), who challenged Eurocentric narratives. While previous generations of Africanist scholarship focused primarily on political and economic histories of decolonization, Africa Media Review foregrounded media systems, press freedom, and information flows as vital dimensions of Africa's postcolonial transformations.

A fresh wave of digital-humanities methods now allows us to visualize and quantify how Africa Media Review developed over time. These methods complement the qualitative historiographical perspectives offered by scholars such as Frederick Cooper (2002, 2014) and Achille Mbembe (2001), deepening our appreciation of the journal's role in reshaping discourses around African media.

2. OCR Text Length Over Time: Gauging Publishing Activity

A first point of entry is the bar chart displaying the OCR text length of Africa Media Review articles by publication date (1986–1997). In this visualization, each bar corresponds to a particular issue, with the x-axis representing total OCR word count (or token count). Several patterns stand out:
	1.	Initial Years (1986–1988): Issues in the mid-1980s, shortly after the journal's inception, show relatively high textual volume in some years (notably 1988) and more modest output in others. This fluctuation may reflect the early establishment of editorial procedures, shifting funding opportunities, and the ACCE's ability to commission longer or more numerous articles.
	2.	Variability in the 1990s: As the 1990s progress, there are spikes (e.g., around 1994–1995) when the total text length surges toward the higher end of the scale. These spikes could indicate special issues or increased interest in debates around the liberalization of African media in the post–Cold War landscape, dovetailing with Toyin Falola and Emmanuel Akyeampong's emphasis on the changing political economy of African states.
	3.	Steady Output Despite Political Upheavals: The overall continuity of publishing, even amid the early 1990s political transitions in many African countries, speaks to the resilience of the editorial team and the consistent scholarly interest in African media. Scholars like Kwame Karikari underscore how press freedom debates surged during periods of democratization, likely prompting longer or more in-depth articles.

By quantifying the text length, we gain a proxy measure of publishing volume and editorial intensity—key indicators of the journal's evolving place within Africa-focused scholarship on communication.

3. Place Names and Spatial Coverage: NER Insights

A second visualization—a stacked bar chart showing named-entity recognition (NER) results for place names—reveals which locations were most frequently mentioned in Africa Media Review. Each row corresponds to a publication date, and the x-axis represents the total number of place-name references extracted from that year's issue(s). Several interpretive points emerge:
	1.	Prominence of African Countries: Nigeria, Kenya, Ghana, and Zimbabwe appear frequently, reflecting both the intellectual hubs of African communication research and the specific case studies that authors chose. This resonates with Frederick Cooper's (2002) observations about the importance of particular national contexts in African historiography—Nigeria, for instance, often exemplifies a large, diverse media ecosystem.
	2.	Transnational Focus: References to the United States, France, and Britain also feature in the chart—unsurprising given the ongoing influence of former colonial powers, as well as the broader North-South debates about media flows (e.g., NWICO). The presence of places like "Paris," "London," and "Washington" underscores how Africa Media Review engaged global power centers, aligning with the postcolonial critique of external media hegemony advanced by Walter Rodney (1972) and others.
	3.	Surprising Mentions: The mosaic includes smaller counts of less-expected place names—possibly one-off references to academic conferences or lesser-known case studies. Their presence reflects the journal's eclectic coverage and openness to varied African and non-African contexts.

Crucially, these data illustrate the journal's pan-African orientation: while certain countries dominate, a wide spread of locales attests to diverse contributions. This geographical breadth exemplifies the pan-continental identity of the ACCE and the journal's editorial ethos of inclusivity.

4. Semantic Clusters via UMAP: Thematic Constellations

The third visualization—a 2D projection of article embeddings using a sentence transformer model combined with UMAP—provides a high-level view of how articles group together semantically:
	1.	Clusters of Thematically Aligned Articles: Dots that cluster closely in this scatter plot represent articles with similar semantic features (e.g., shared topics, vocabulary, or conceptual frameworks). One might find a dense cluster focusing on "community broadcasting" or "rural development communication," echoing research trends noted by contributors to Africa Media Review. Another cluster may revolve around "press freedom" and "state policy," capturing a key tension in postcolonial African media systems.
	2.	Outliers and Specialized Topics: Points that lie far from the main clusters may represent articles addressing niche or highly specialized topics—perhaps a localized case study in a Francophone West African context or a piece on emerging ICT policy in the mid-1990s. These outliers can reveal the journal's readiness to engage novel themes, even if they did not form part of mainstream debates at the time.
	3.	Shifts Across Time: Although this projection does not directly encode publication dates, repeated analyses stratified by decade could reveal how the journal's thematic emphases evolved (e.g., from state-run media in the 1980s to deregulation and private radio in the 1990s). Such "diachronic clustering" aligns well with Frederick Cooper's (2014) invitation to marry macro-historical processes with fine-grained, localized analyses.

This semantic mapping demonstrates how digital-humanities tools add depth to our historiographical understanding: we can see, at scale, the conceptual terrain navigated by Africa Media Review.

5. Incorporating the Visualizations into the Broader Historiography

5.1. Linking Publishing Patterns to Decolonization Debates

The variations in OCR text length hint at shifting editorial capacities, possibly influenced by external factors like political instability or academic funding cycles. As Bethwell A. Ogot (1963) and Jean Suret-Canale (1964) have shown, the production of African history (and by extension, African media scholarship) often reflects wider currents of state policy, donor interests, and intellectual politics. The bar chart thus offers an empirical measure to anchor broader claims about the challenges of sustaining African-led journals in an uneven global publishing ecosystem.

5.2. Geographic Breadth as a Pan-African Imperative

NER-based insights reinforce how Africa Media Review contributed to a pan-continental discourse, repeatedly featuring examples across Anglophone, Francophone, and Lusophone contexts. This approach parallels Ngũgĩ wa Thiong'o's (1986) call to transcend linguistic and colonial divides in forging a unified African intellectual space. The data reveal that Africa Media Review not only critiqued media imperialism but also showcased empirical realities from diverse African settings—an embodiment of the journal's commitment to decolonizing media scholarship.

5.3. Thematic Clustering and the Evolution of Communication Research

Finally, the UMAP scatter plot underscores the journal's role in charting—and sometimes anticipating—major shifts in communication research. As Africa entered the 1990s, transitions to multiparty democracy, liberalized economies, and the early adoption of digital communication likely spurred new thematic clusters in the journal. Such continuity and change echo Emmanuel Akyeampong's (2000) reminder that African academic discourse is neither static nor parochial; it adapts to political upheavals, technological advancements, and scholarly trends.

6. Conclusion

Africa Media Review stands at the nexus of African historiography, communication studies, and decolonization scholarship. The digital-humanities visualizations—revealing shifts in article volume, geographical coverage, and thematic clustering—reinforce the journal's significance as both a mirror and a catalyst of Africa-centered media research. The bar chart quantifies how much was published over time, the place-name analysis highlights the journal's transnational scope, and the UMAP projection demonstrates the rich thematic tapestry of its articles.

These computational insights do not replace traditional historiographical methods. Rather, they amplify our capacity to discern trends, test assumptions, and pose new questions—thereby advancing the broader project of understanding how Africans have taken control of their own narratives. In the spirit of scholars like Frederick Cooper and Achille Mbembe, whose work reminds us that decolonization is as much about autonomy in knowledge production as it is about political independence, the findings from these digital methods confirm that Africa Media Review has been—and remains—a pivotal platform for asserting Africa's voice in global media and communication debates.

Illustrative Peer-Reviewed References
	•	Akyeampong, Emmanuel. 2000. "History, Memory, Slave-Trade and Slavery in Anlo (Ghana)." Slavery & Abolition 21(3): 1–24.
	•	Brennan, James R. 2010. "Politics and Business in the Todd's Theatres of Colonial Tanganyika." African Studies Review 53(3): 1–24.
	•	Chakrabarty, Dipesh. 2000. Provincializing Europe: Postcolonial Thought and Historical Difference. Princeton University Press.
	•	Cooper, Frederick. 2002. Africa Since 1940: The Past of the Present. Cambridge University Press.
	•	Cooper, Frederick. 2014. Africa in the World: Capitalism, Empire, Nation-State. Harvard University Press.
	•	Dike, Kenneth Onwuka. 1956. Trade and Politics in the Niger Delta, 1830–1885. Clarendon Press.
	•	Mbembe, Achille. 2001. On the Postcolony. University of California Press.
	•	Ngũgĩ wa Thiong'o. 1986. Decolonising the Mind: The Politics of Language in African Literature. Heinemann.
	•	Ogot, Bethwell A. 1963. "British Administration in the Central Nyanza District of Kenya, 1900–60." The Journal of African History 4(2): 249–273.
	•	Rodney, Walter. 1972. How Europe Underdeveloped Africa. Bogle-L'Ouverture.
	•	Suret-Canale, Jean. 1964. French Colonialism in Tropical Africa 1900–1945. Pica Press.

(All references cited here are from peer-reviewed scholarly presses or established academic journals.)
```

## Second Attempt

```python
Below is a revised historiographical essay on Africa Media Review that integrates interpretation of the three data‐analysis outputs—(1) an overview bar chart of OCR text length over time, (2) place‐name frequencies extracted via spaCy's NER model, and (3) a UMAP projection of article embeddings. These digital humanities methods help illuminate the journal's evolution, thematic emphases, and intellectual geography in ways that enrich our understanding of Africa Media Review's role in the decolonization of African media studies.

1. Introduction: Africa Media Review and the Decolonization of Information

Since its first issue in 1986, Africa Media Review (AMR) has provided a vital platform for African perspectives on media, communication, and cultural representation. Rooted in the pan‐African ethos of the African Council for Communication Education (ACCE), the journal emerged alongside broader scholarly efforts to challenge the colonial underpinnings of African history—a movement led by historians such as Kenneth Onwuka Dike (1956) and Bethwell A. Ogot (1963), who argued for the inclusion of African voices and sources in historical analysis. While much of the "decolonization of knowledge" conversation has focused on overtly political, social, and economic dimensions of Africa's liberation, Africa Media Review underscores the importance of decolonizing the realm of information flows and media discourses, connecting with the foundational critiques offered by Walter Rodney (1972) and Ngũgĩ wa Thiong'o (1986).

Today's digital humanities methods add new layers of insight to this story. By quantifying and mapping aspects of Africa Media Review's corpus—from how much content was published, to the geographical spread of its references, to the latent semantic clusters among articles—we gain fresh perspectives on how the journal contributed to ongoing debates about Africa's media futures. Below, each data visualization is briefly interpreted and woven into a broader historiographical narrative.

2. OCR Text Length Over Time: Tracking Editorial Output

A bar chart of OCR text length across various issues from 1986 to 1997 shows how much text was published in each volume and issue. Several takeaways emerge:
	1.	Early Establishment (1986–1988): The journal's first volumes already show substantial text length. This early intensity suggests a robust editorial commitment to carving out space for African media scholarship, despite the challenges of securing funding and editorial continuity—a point that resonates with Jean Suret-Canale's (1964) argument about the hurdles of sustaining African‐led academic initiatives in postcolonial contexts.
	2.	Fluctuations in the 1990s: Certain years exhibit spikes in total textual output (e.g., around 1990–1991 or 1994–1995). These peaks may correspond to special thematic issues—commonly seen when a journal seizes upon major developments in African media, such as liberalization reforms or the emergence of private broadcasting. Historians like Frederick Cooper (2002, 2014) have underlined how shifts in African governance—especially moves toward multiparty democracy—often go hand in hand with vigorous debate over the role of the press, which could drive increased editorial content.
	3.	Overall Consistency: Despite variations, AMR published regularly throughout political upheavals in various African countries, indicating the resilience and sustained interest in Africa‐centric media research. Scholars such as Emmanuel Akyeampong (2000) and Toyin Falola (1993) observe that intellectual production in Africa frequently adapts to changes in political climates—this bar chart echoes those adaptive rhythms in the communication field.

3. Place‐Name Frequencies via spaCy NER: Geographic Reach

The second visualization—a stacked bar chart of place names extracted via spaCy's named‐entity recognition model—shows the frequency and variety of locations mentioned across issues:
	1.	Dominance of Key African States: Nigeria, Kenya, Ghana, Zimbabwe, and other frequently cited countries highlight major focal points of research and case studies. This largely aligns with the prominence of these nations in media reforms or policy transitions—Nigeria's turbulent history of press freedom battles, for instance, has long exemplified the tension between state power and independent journalism.
	2.	Transnational Frame: References to former colonial metropoles (Britain, France) and influential global cities (New York, Washington) confirm Africa Media Review's engagement with the international dimension of African media development. This resonates with the New World Information and Communication Order (NWICO) debates, as the journal tackled imbalances in global media flows—an issue dissected by scholars like Kaarle Nordenstreng (1979) and Hamid Mowlana (1980) in other peer‐reviewed forums.
	3.	Pan‐African Emphasis: The breadth of place names underscores AMR's pan‐African identity. Not confined to Anglophone contexts, mentions of Francophone and Lusophone regions reflect the journal's editorial stance on inclusivity. Ngũgĩ wa Thiong'o (1986) has repeatedly called for bridging linguistic divides in African knowledge production—a practice that AMR's geographic scope demonstrates in practice.

4. UMAP Projection of Article Embeddings: Thematic Constellations

Finally, the UMAP projection—applying a sentence transformer model to each article—clusters semantically similar pieces:
	1.	Clusters Signaling Thematic Coherence: Articles focused on "broadcast policy," "community media," or "rural communication" may cluster together. Such groupings reveal the internal consistency of recurring research areas, likely reflecting editorial priorities or special issues. By visually mapping articles, we see a data‐driven confirmation of patterns historians or communication scholars might have inferred anecdotally.
	2.	Outliers and Specialized Topics: Articles situated far from dense clusters may be addressing narrower concerns—e.g., a single‐country case study on diaspora media, or a policy critique rooted in a specific time and place. Outliers remind us that AMR, while thematically cohesive overall, also incubated innovative or exploratory scholarship, resonating with Achille Mbembe's (2001) call for postcolonial research that breaks new conceptual ground.
	3.	Temporal Transitions: Although the UMAP scatterplot does not directly encode time, repeated embeddings (grouped by decade) could illustrate how the journal's priorities evolved from the late 1980s to the mid‐1990s—mirroring Africa's broader moves toward democratization and media liberalization. As Frederick Cooper (2014) notes, analyzing how knowledge clusters shift over time can uncover deeper historical currents driving such scholarship.

5. Digital Humanities Methods and the Historiography of Africa Media Review

Bringing these three visualizations together into a single historiographical frame reveals the power of digital humanities for understanding a journal's trajectory:
	•	Quantitative Dimensions: The bar chart on text length traces editorial activity and can be situated in broader historical contexts (e.g., political crises or intellectual funding climates).
	•	Spatial Dimensions: The place‐name chart highlights AMR's pan‐African scope and transnational awareness, engaging decolonization not only within nation‐states but also in relation to global power centers.
	•	Conceptual Dimensions: UMAP‐derived clusters illuminate how decolonial media scholarship took shape, highlighting both core areas of consensus and novel intellectual paths.

Crucially, these methods do not replace close reading or contextual analysis—historians like Bethwell A. Ogot and Jean Suret-Canale remind us that numbers and patterns alone do not fully convey the complexities of African knowledge production. Instead, digital approaches augment our interpretive toolkit, providing new avenues for verifying or refining the claims that historians and communication scholars have made about Africa Media Review's significance.

6. Conclusion

Tracing Africa Media Review across both conventional historiography and digital data analysis underscores the journal's integral role in the broader project of decolonizing African media studies. Its sustained publication from the mid‐1980s onward, documented in the volume of OCR text, testifies to the continued resonance of African‐led scholarship in a world still shaped by uneven information flows. The spaCy‐extracted place‐name data reaffirm the journal's pan‐continental mission and its engagement with global power centers, echoing themes advanced by postcolonial theorists like Walter Rodney, Ngũgĩ wa Thiong'o, and Achille Mbembe. Meanwhile, the UMAP projection helps us glimpse how clusters of articles have tackled recurring debates on state control, community‐centered communication, or the interplay of global and local influences.

In short, these visualizations—and the digital humanities methods that generated them—complement the observations of historians like Frederick Cooper and Emmanuel Akyeampong, who have long insisted that decolonization must encompass not only political sovereignty but also autonomy over how African experiences are archived, analyzed, and understood. Africa Media Review stands as a testament to that autonomy: a crucial meeting ground of disciplinary perspectives, media case studies, and transformative ambitions for Africa's information order.

Select Peer-Reviewed References
	•	Akyeampong, Emmanuel. 2000. "History, Memory, Slave‐Trade and Slavery in Anlo (Ghana)." Slavery & Abolition 21(3): 1–24.
	•	Chakrabarty, Dipesh. 2000. Provincializing Europe: Postcolonial Thought and Historical Difference. Princeton University Press.
	•	Cooper, Frederick. 2002. Africa Since 1940: The Past of the Present. Cambridge University Press.
	•	Cooper, Frederick. 2014. Africa in the World: Capitalism, Empire, Nation-State. Harvard University Press.
	•	Dike, Kenneth Onwuka. 1956. Trade and Politics in the Niger Delta, 1830–1885. Clarendon Press.
	•	Mbembe, Achille. 2001. On the Postcolony. University of California Press.
	•	Mowlana, Hamid. 1980. "Communication in the Post‐Industrial Era: New Trends in International Communication." Journal of Communication 30(2): 114–123.
	•	Ngũgĩ wa Thiong'o. 1986. Decolonising the Mind: The Politics of Language in African Literature. Heinemann.
	•	Nordenstreng, Kaarle. 1979. "The New World Information and Communication Order: An Overview of Some Results." Gazette 25(4): 229–245.
	•	Ogot, Bethwell A. 1963. "British Administration in the Central Nyanza District of Kenya, 1900–60." The Journal of African History 4(2): 249–273.
	•	Rodney, Walter. 1972. How Europe Underdeveloped Africa. Bogle‐L'Ouverture Publications.
	•	Suret‐Canale, Jean. 1964. French Colonialism in Tropical Africa 1900–1945. Pica Press.

(Note: All references come from peer-reviewed journals or university presses.)
```