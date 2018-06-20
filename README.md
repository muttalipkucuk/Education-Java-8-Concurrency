https://examples.javacodegeeks.com/core-java/util/concurrent/completablefuture/java-completionstage-completablefuture-example/

http://millross-consultants.com/completion-stage-future-introduction.html

Interface CompletionStage<T>

Interface Future<V>

Class CompletableFuture<T> implements Future<T>, CompletionStage<T>







CompletableFuture supplyAsync() API

public static CompletableFuture supplyAsync(Supplier supplier)
public static CompletableFuture supplyAsync(Supplier supplier, Executor executor)



CompletableFuture runAsync() API

public static CompletableFuture runAsync(Runnable runnable)
public static CompletableFuture runAsync(Runnable runnable, Executor executor)



The thenApply Method

