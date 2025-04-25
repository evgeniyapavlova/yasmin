<script>
	import { base } from '$app/paths';
	import { searchString } from '$lib/stores/affs';
	import Tg from './Tg.svelte';
	import Photo from './Photo.svelte';
</script>

<section class="title">
	<h2>TREINAMENTO SEM CUSTO PARA ASPIRANTES A TRADERS</h2>
	<h1>Como Usar Sistemas para Extrair Lucros dos Mercados</h1>
	<h3>...sem Análises Discricionárias Inúteis!</h3>
</section>

<section class="content">
	<div class="content-photo">
		<Photo />
		<div class="content-photo-caption">
			Mais de 100.000 traders já usaram minha estratégia e tiveram lucro
		</div>
	</div>
	<div class="content-cta">
		<div class="cta">
			<a href="https://trade.casatrade.com/en/register{$searchString}" class="button">
				SIM! Assista ao Treinamento Agora!
				<svg
					version="1.1"
					id="Layer_1"
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink"
					x="0px"
					y="0px"
					viewBox="0 0 120.64 122.88"
					style="enable-background:new 0 0 120.64 122.88"
					xml:space="preserve"
					preserveAspectRatio="none"
					><g
						><path
							d="M54.03,108.91c-1.55,1.63-2.31,3.74-2.28,5.85c0.03,2.11,0.84,4.2,2.44,5.79l0.12,0.12c1.58,1.5,3.6,2.23,5.61,2.2 c2.01-0.03,4.01-0.82,5.55-2.37c17.66-17.66,35.13-35.61,52.68-53.4c0.07-0.05,0.13-0.1,0.19-0.16c1.55-1.63,2.31-3.76,2.28-5.87 c-0.03-2.11-0.85-4.21-2.45-5.8l-0.27-0.26C100.43,37.47,82.98,19.87,65.46,2.36C63.93,0.82,61.93,0.03,59.92,0 c-2.01-0.03-4.03,0.7-5.61,2.21l-0.15,0.15c-1.57,1.58-2.38,3.66-2.41,5.76c-0.03,2.1,0.73,4.22,2.28,5.85l47.22,47.27 L54.03,108.91L54.03,108.91z M2.26,106.91c-1.54,1.62-2.29,3.73-2.26,5.83c0.03,2.11,0.84,4.2,2.44,5.79l0.12,0.12 c1.57,1.5,3.6,2.23,5.61,2.21c2.01-0.03,4.02-0.82,5.55-2.37C31.01,101.2,48.87,84.2,66.39,67.12c0.07-0.05,0.14-0.11,0.21-0.17 c1.55-1.63,2.31-3.76,2.28-5.87c-0.03-2.11-0.85-4.21-2.45-5.8C48.94,38.33,31.36,21.44,13.83,4.51l-0.12-0.13 c-1.53-1.54-3.53-2.32-5.54-2.35C6.16,2,4.14,2.73,2.56,4.23L2.41,4.38C0.84,5.96,0.03,8.05,0,10.14c-0.03,2.1,0.73,4.22,2.28,5.85 l47.18,45.24L2.26,106.91L2.26,106.91z"
						/>
					</g>
				</svg>
			</a>

			<Tg>Alguma outra dúvida?</Tg>
		</div>
		<picture>
			<source srcset="{base}/images/tp.avif" type="image/avif" />
			<source srcset="{base}/images/tp.webp" type="image/webp" />
			<img src="{base}/images/tp.jpg" alt="Trustpilot" />
		</picture>
	</div>

	<div class="content-text">
		<h2>TREINAMENTO EXCLUSIVO:</h2>
		<ul class="content-list">
			<li>
				<strong>A abordagem pouco conhecida</strong> usada pela maioria dos traders de sucesso que não
				requer longas horas na frente da tela.
			</li>
			<li>
				<strong>A ferramenta única e poderosa</strong> para criar sistemas de trading com uma vantagem nos
				mercados, mesmo que você não se considere um gênio da computação.
			</li>
			<li>
				<strong>Como gerenciar o risco com um portfólio bem diversificado</strong> mesmo que você não tenha
				milhões.
			</li>
		</ul>
	</div>
</section>

<section class="content-note">
	<h4>NOTA: Este Treinamento NÃO é para Todos...</h4>
	<p class="content-note-large">
		Nem todos podem se tornar traders lucrativos. Seus resultados não são garantidos. Este treinamento é
		único para aqueles que são trabalhadores, percebem que o sucesso não vem facilmente e estão dispostos a
		fazer o trabalho quando surgirem problemas. Este treinamento, no entanto, irá lhe dar uma visão sobre um
		dos maiores traders sistemáticos de todos os tempos!
	</p>
	<p class="content-note-small">
		Nada nesta página, em nossos sites ou em qualquer um de nossos conteúdos ou currículos é uma promessa ou
		garantia de resultados ou ganhos futuros, e não oferecemos aconselhamento legal, médico, fiscal ou outro
		aconselhamento profissional. Qualquer número financeiro mencionado aqui ou em nossos sites é apenas para
		ilustrar conceitos e não deve ser considerado como ganhos médios, ganhos exatos ou promessas de desempenho
		futuro. Use cautela e consulte sempre seu contador, advogado ou conselheiro profissional antes de agir
		baseado nessas ou em outras informações relacionadas a mudanças no estilo de vida, negócios ou finanças.
		Você é o único responsável pelas suas decisões, ações e resultados na vida, e ao se registrar aqui você
		acompanha que não tentará nos responsabilizar por suas decisões, ações ou resultados, em nenhum momento,
		sob nenhuma circunstância.
		<br /> <br />
		Este site não faz parte do site do Facebook ou do Facebook Inc. Além disso, este site NÃO é endossado pelo
		Facebook de nenhuma forma. FACEBOOK é uma marca registrada do FACEBOOK, Inc.
	</p>
</section>
