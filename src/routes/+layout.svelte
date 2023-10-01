<script>
	import '../app.css';
</script>

<!-- <button class="btn">Hello daisyUI</button> -->
<!-- <div class="navbar bg-base-100"> -->
<div class="navbar bg-slate-300">
  <div class="flex-1">
    <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
  </div>
  <div class="flex-none">
    <ul class="menu menu-horizontal px-1">
      <li><a href="/bktest">Link</a></li>
      <li>
        <details>
          <summary>
            Parent
          </summary>
          <ul class="p-2 bg-base-100">
            <li><a>Link 1</a></li>
            <li><a>Link 2</a></li>
          </ul>
        </details>
      </li>
    </ul>
  </div>
</div>

<slot />


<footer class="footer p-10 bg-base-200 text-base-content">
	<nav>
	  <header class="footer-title">Services</header> 
	  <a class="link link-hover">Branding</a> 
	  <a class="link link-hover">Design</a> 
	  <a class="link link-hover">Marketing</a> 
	  <a class="link link-hover">Advertisement</a>
	</nav> 
	<nav>
	  <header class="footer-title">Company</header> 
	  <a class="link link-hover">About us</a> 
	  <a class="link link-hover">Contact</a> 
	  <a class="link link-hover">Jobs</a> 
	  <a class="link link-hover">Press kit</a>
	</nav> 
	<nav>
	  <header class="footer-title">Legal</header> 
	  <a class="link link-hover">Terms of use</a> 
	  <a class="link link-hover">Privacy policy</a> 
	  <a class="link link-hover">Cookie policy</a>
	</nav> 
	<form>
	  <header class="footer-title">Newsletter</header> 
	  <fieldset class="form-control w-80">
		<label class="label">
		  <span class="label-text">Enter your email address</span>
		</label> 
		<div class="relative">
		  <input type="text" placeholder="username@site.com" class="input input-bordered w-full pr-16" /> 
		  <button class="btn btn-primary absolute top-0 right-0 rounded-l-none">Subscribe</button>
		</div>
	  </fieldset>
	</form>
  </footer>
