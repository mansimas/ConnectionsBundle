AbstractStartServiceCommand
===========================

This is an abstract class for creating console commands which use any service's (which, in turn, is using pipeline) functionality.

It adds default ``target`` parameter, benchmark (see `CommandBenchmark documentation <command_benchmark.rst>`_) and calls services' startPipeline method.

It is the base class for all of the ConnectionsBundle's console commands.
