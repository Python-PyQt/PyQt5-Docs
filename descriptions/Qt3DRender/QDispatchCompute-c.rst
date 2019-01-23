.. sip:class-description::
    :status: todo
    :brief: FrameGraph node to issue work for the compute shader on GPU
    :realname: Qt3DRender::QDispatchCompute
    :digest: 8a9e7ccb057f62f6b0fde3180af14150

FrameGraph node to issue work for the compute shader on GPU.

A :sip:ref:`~PyQt5.Qt3DRender.QDispatchCompute` allows work to be issued for the compute shader to run on the GPU. The workGroupX, workGroupY and workGroupZ properties specify the work group sizes for the compute shader invocation. QComputeCommand components need to be added to entities to instruct Qt3D to select the materials and geometry from the entities for the compute invocation. The work group sizes for the shader invocation will be the maximum of the work group sizes specified in :sip:ref:`~PyQt5.Qt3DRender.QDispatchCompute` and QComputeCommand.
