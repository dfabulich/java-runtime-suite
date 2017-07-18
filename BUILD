java_binary(
	name='x',
	srcs=['X.java'],
	main_class='X',
)

java_runtime(
	name='jdk-darwin',
	srcs=[],
	java_home='/Library/Java/JavaVirtualMachines/jdk1.8.0_112.jdk/Contents/Home',
)

java_runtime_suite(
	name='jdk',
	runtimes = {
		'darwin': ':jdk-darwin',
	}
)