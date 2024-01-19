<script lang="ts">
</script>

<div class="card p-4 variant-filled-surface">
	<div class="flex flex-col gap-4 items-center-justify-center">
		<label class="label">
			<span>Input</span>
			<input type="text" placeholder="Input" />
		</label>
		<label class="label">
			<span>Input</span>
			<input class="input" type="text" placeholder="Input" />
		</label>
		<label class="label">
			<span>Select</span>
			<select class="select">
				<option value="1">Option 1</option>
				<option value="2">Option 2</option>
				<option value="3">Option 3</option>
				<option value="4">Option 4</option>
				<option value="5">Option 5</option>
			</select>
		</label>
		<label class="label">
			<span>Textarea</span>
			<textarea
				class="textarea"
				rows="4"
				placeholder="Lorem ipsum dolor sit amet consectetur adipisicing elit."
			/>
		</label>
		<div class="space-y-2">
			<label class="flex items-center space-x-2">
				<input class="checkbox" type="checkbox" checked />
				<p>Option 1</p>
			</label>
			<label class="flex items-center space-x-2">
				<input class="checkbox" type="checkbox" />
				<p>Option 2</p>
			</label>
			<label class="flex items-center space-x-2">
				<input class="checkbox" type="checkbox" />
				<p>Option 3</p>
			</label>
		</div>
		<p>Amount</p>
		<div class="input-group input-group-divider grid-cols-[auto_1fr_auto]">
			<div class="input-group-shim">(icon)</div>
			<input type="text" placeholder="Amount" />
			<select>
				<option>USD</option>
				<option>CAD</option>
				<option>EURO</option>
			</select>
		</div>
		<div class="flex flex-row gap-4 items-center justify-around">
			<button type="button" class="btn-icon variant-filled">(icon)</button>
			<button type="button" class="btn variant-filled">Button</button>
			<button type="button" class="btn variant-filled">
				<span>(icon)</span>
				<span>Button</span>
			</button>
		</div>
		<div class="flex flex-row gap-4 items-center justify-around">
			<a href="/" class="btn-icon variant-filled">(icon)</a>
			<a href="/" class="btn variant-filled">a</a>
			<a href="/" class="btn variant-filled">
				<span>(icon)</span>
				<span>Anchor</span>
			</a>
		</div>
		<div class="btn-group-vertical variant-filled max-w-xs">
			<button>Months</button>
			<button>Days</button>
			<button>Years</button>
		</div>
	</div>
</div>
