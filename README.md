Code lies in "akka/src/main/cluster/sample/cluster/allreduce/"

Run Master: sbt "runMain sample.cluster.Allreduce.AllreduceMaster"

Run Worker: sbt "runMain sample.cluster.Allreduce.AllreduceWorker $PORT"
