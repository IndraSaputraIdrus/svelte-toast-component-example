<div class="container">
	<button class="success">Success</button>
	<button class="info">Info</button>
	<button class="warning">Warning</button>
	<button class="error">Error</button>
</div>

<style>
	.container {
		width: 18rem;
		display: grid;
		gap: 1rem;
		grid-template-rows: repeat(4, 1fr);
		padding: 1rem;
		background-color: var(--secondary);
		border-radius: 0.5rem;

		button {
			padding: 10px 0px;
			border: none;
			color: var(--secondary);
			font-weight: 600;
			border-radius: 0.375rem;

			&:hover {
				opacity: 85%;
			}

			&:focus {
				outline: none;
			}

			&.success {
				background-color: var(--toast-success);
			}

			&.info {
				background-color: var(--toast-info);
			}

			&.warning {
				background-color: var(--toast-warning);
			}

			&.error {
				background-color: var(--toast-error);
			}
		}
	}
</style>
