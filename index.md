<head>
<script>
//Read idtoken from query parameter with the same name.
const params = new Proxy(new URLSearchParams(window.location.search), {
	get: (searchParams, prop) => searchParams.get(prop),
	});
	const idToken = params.idtoken;
	window.getGliaContext = () => ({ idToken });
</script>
  
<script async src="https://api.beta.glia.com/salemove_integration.js"></script>
</head>


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean vestibulum hendrerit ante, nec convallis tellus luctus vel. Integer in ante vitae lectus vulputate vestibulum. Etiam euismod gravida arcu a fringilla. Fusce nec sapien et lorem lobortis euismod. Vestibulum neque nisl, congue ac dolor vitae, sodales lobortis ante. Ut facilisis efficitur varius. Duis consectetur ante tellus, eget lobortis elit fermentum eu. Suspendisse vehicula rhoncus ante sit amet porttitor. Phasellus ut nunc rhoncus, dignissim mauris id, posuere neque. Maecenas nulla elit, sollicitudin vel urna ut, tincidunt vehicula lacus. Nunc imperdiet euismod lacinia. Sed eu tristique lacus. Quisque porttitor nibh vel ullamcorper semper.

Aenean eu justo non mi sagittis iaculis. Etiam ultrices condimentum nunc et dictum. Quisque vitae neque suscipit, feugiat eros quis, tempor ipsum. Suspendisse cursus egestas ultrices. Praesent eu semper diam. Pellentesque accumsan ac lacus eget tempor. Vestibulum ut dignissim ipsum, quis maximus ante. Maecenas consequat nulla quis ipsum pretium accumsan. Phasellus a enim luctus, lacinia magna ut, porta ante.


[TestPage](veelyksleht.md) | [Credit Card options](CreditCardOptions.md)

<button
  class="omnibrowse-code-button"
  onclick="document.body.appendChild(document.createElement('sm-visitor-code'))">   Get CoBrowsing code </button>
