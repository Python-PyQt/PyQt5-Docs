.. sip:method-description::
    :status: todo
    :pysig: f10f4aa90c0dd38586dccc2d562aa18b
    :realsig: ()
    :digest: 7ab2f829db121ee070bb548753e475c3

Returns a list of all registered devices.

**Note:** The returned list cannot be used to add new devices. To add a simulated touch screen for an autotest, QTest::createTouchDevice() can be used. To add real touch screens to QPA plugins, the private ``QWindowSystemInterface::registerTouchDevice()`` function can be used.
