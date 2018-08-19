<h1><a id="Kernel_Maker_0"></a>Kernel Maker</h1>
<h1><a id="Importante_2"></a>Importante</h1>
<ul>
<li>usar gnome terminal com:</li>
</ul>
<pre><code class="language-sh">$ sudo gnome-terminal
</code></pre>
<ul>
<li>dar permissao de execução aos arquivos:</li>
</ul>
<pre><code class="language-sh">$ chmod +x installDependencies KernelMake bootInKernel removeKernel
</code></pre>
<h1><a id="Ordem_de_Uso_12"></a>Ordem de Uso</h1>
<ul>
<li>Instalando dependencias</li>
</ul>
<pre><code class="language-sh">$ ./installDependencies
</code></pre>
<ul>
<li>Configurando e Copilando Kernel</li>
</ul>
<pre><code class="language-sh">$ ./KernelMake
</code></pre>
<ul>
<li>Dentro das configurações escolher drivers opicionais para uso</li>
<li>Apos todas configurações todo log de instalação com o tempo de execução estará na pasta nova chamada logsConfig</li>
<li>Para bootar no novo kernel:</li>
</ul>
<pre><code class="language-sh">$ ./bootInNewKernel &lt;Nome Do Kernel&gt;
</code></pre>
<ul>
<li>(opcional) removendo kernel</li>
</ul>
<pre><code class="language-sh">$ ./removeKernel &lt;Nome Do Kernel&gt;
</code></pre>
