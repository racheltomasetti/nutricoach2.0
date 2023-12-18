<script>
    import foodImage from '$lib/images/fooddiary.jpg';
</script>

<svelte:head>
	<title>Login</title>
	<meta name="description" content="Login portal" />
</svelte:head>

<main>
	<section class="vh-75" style="background: linear-gradient(to right, #9681ff, hsl(0, 0%, 91%));">
		<div class="container py-5 h-100">
		<div class="row d-flex justify-content-center align-items-center h-100">
			<div class="col-12 col-md-8 col-lg-6 col-xl-5">
			<div class="card shadow-2-strong" style="border-radius: 1rem;">
				<div class="card-body p-5 text-center">
	
				<h3 class="mb-5">Sign in</h3>
	
				<div class="form-outline mb-4">
					<input type="email" id="typeEmailX-2" class="form-control form-control-lg" />
					<label class="form-label" for="typeEmailX-2">Email</label>
				</div>
	
				<div class="form-outline mb-4">
					<input type="password" id="typePasswordX-2" class="form-control form-control-lg" />
					<label class="form-label" for="typePasswordX-2">Password</label>
				</div>
	
				<!-- Checkbox -->
				<div class="form-check d-flex justify-content-start mb-4">
					<input class="form-check-input" type="checkbox" value="" id="form1Example3" />
					<label class="form-check-label" for="form1Example3"> Remember password </label>
				</div>
	
				<a href="login/views/admin" type="submit" class="btn btn-lg btn-block" >Login</a>
	
				<hr class="my-4">
	
				</div>
			</div>
			</div>
		</div>
		</div>
	</section>
</main>



  <style>
	.btn{
        background-color: #6748ff;
        color: #ffffff;
    }
  </style>