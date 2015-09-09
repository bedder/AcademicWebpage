---
layout: default
---

## Papers

<div class="publication" id="zhang2015automated">
	<span class="authors">Z. Zhang, M. Bedder, S.L. Smith, D. Walker, S. Shabir, J. Southgate</span>
	<span class="year">(2015)</span>
	<span class="title">"Automated Motion Analysis of Adherent Cells in Monolayer Culture"</span>,
	<span class="location">Proceedings of the 10th International Conference on Information Processing in Cells and Tissues (IPCAT'15)</span>
	<span class="notes">(To appear)</span>
	<div class="links">
		<span class="links_abstract">[<a href="#zhang2015automated_abstract" class="reveal" rel="zhang2015automated_abstract">Abstract</a>]</span>
		<span class="links_pdf">[<a href="http://link.springer.com/chapter/10.1007/978-3-319-23108-2_16">PDF at Springer Link</a>]</span>
		<span class="links_bibtex">[<a href="#zhang2015automated_bibtex" class="reveal" rel="zhang2015automated_bibtex">bibTeX</a>]</span>
	</div>
	<div class="abstract" id="zhang2015automated_abstract">
		This paper presents a novel method for tracking and characterizing adherent cells in monolayer culture. A system of cell tracking employing computer vision techniques was applied to time-lapse videos of replicate normal human uro-epithelial cell cultures exposed to different concentrations of adenosine triphosphate (ATP), acquired over a 20 hour period. Subsequent analysis, comprising feature extraction, demonstrated the ability of the technique to successfully separate the modulated classes of cell.
	</div>
	<pre class="bibtex" id="zhang2015automated_bibtex">
@inproceedings{
	zhang2015automated,
	title={Automated Motion Analysis of Adherent Cells in Monolayer Culture},
	author={Zhang, Zhen and Bedder, Matthew and Smith, Stephen L and Walker, Dawn and Shabir, Saqib and Southgate, Jennifer},
	booktitle={Proceedings of the 10th International Conference on Information Processing in Cells and Tissues},
	year={2015},
	publisher={Springer},
	series={LNCS}
}</pre>
</div>

<br/>

## Journals

<div class="publication" id="smith2015computational">
	<span class="authors">S.L. Smith, M.A. Lones, M. Bedder, J.E. Alty, J. Cosgrove, R.J. Maguire, M.E. Pownall, D. Ivanoiu, C. Lyle, A. Cording, C.J.H. Elliott</span>
	<span class="year">(2015)</span>
	<span class="title">"Computational approaches for understanding the diagnosis and treatment of Parkinson’s disease"</span>,
	<span class="location">IET Systems Biology</span>
	<span class="notes"></span>
	<div class="links">
		<span class="links_abstract">[<a href="#smith2015computational_abstract" class="reveal" rel="smith2015computational_abstract">Abstract</a>]</span>
		<span class="links_pdf">[<a href="http://digital-library.theiet.org/content/journals/10.1049/iet-syb.2015.0030">PDF at IET Digital Library</a>]</span>
		<span class="links_bibtex">[<a href="#smith2015computational_bibtex" class="reveal" rel="smith2015computational_bibtex">bibTeX</a>]</span>
	</div>
	<div class="abstract" id="smith2015computational_abstract">
		This study describes how the application of evolutionary algorithms (EAs) can be used to study motor function in humans with Parkinson's disease (PD) and in animal models of PD. Human data is obtained using commercially available sensors via a range of non-invasive procedures that follow conventional clinical practice. EAs can then be used to classify human data for a range of uses, including diagnosis and disease monitoring. New results are presented that demonstrate how EAs can also be used to classify fruit flies with and without genetic mutations that cause Parkinson's by using measurements of the proboscis extension reflex. The case is made for a computational approach that can be applied across human and animal studies of PD and lays the way for evaluation of existing and new drug therapies in a truly objective way.
	</div>
	<pre class="bibtex" id="smith2015computational_bibtex">
@article{
	smith2015computational,
	title={Computational approaches for understanding the diagnosis and treatment of Parkinson's disease},
	author={Smith, Stephen L and Lones, Michael A and Bedder, Matthew and Alty, Jane E and Cosgrove, Jeremy and Maguire, Richard J and Pownall, Mary Elizabeth and Ivanoiu, Diana and Lyle, Camille and Cording, Amy and others},
	journal={IET Systems Biology},
	year={2015},
	publisher={IET}
}</pre>
</div>


<script src="{{ site.baseurl }}/js/jquery.min.js"></script>
<script>
$('.links_abstract').show();
$('.links_bibtex').show();
$('.reveal').click(function() {
	var id = $(this).attr('rel');
	$('#' + id).slideToggle('slow');
});
</script>